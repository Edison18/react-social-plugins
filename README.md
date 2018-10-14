# React Social Plugins

## Install

Install the component using [NPM](https://www.npmjs.com/):

```sh
$ npm install --save react-social-plugins
```

## Usage

### Initialise module

```js
import {
  LinkedinCompanyProfile,
  LinkedinFollowCompany,
  LinkedinLogin,
  LinkedinAddProfile,
  LinkedinProfile,
  LinkedinShare
} from 'react-social-plugins';
```

### Render
- [Linkedin Follow Company](#linkedin-follow-company)
- [Linkedin Login](#linkedin-login)
- [Linkedin Add Profile](#linkedin-add-profile)
- [Linkedin Profile](#linkedin-profile)
- [Linkedin Company Profile](#linkedin-company-profile)
- [Linkedin Share](#linkedin-share)

#### Linkedin Follow Company
Renders a "Follow" button for a company

```html
<LinkedinFollowCompany
  companyId={12312312}
  counter="top" // Or "right"
  lang="en_US"
/>
```

#### Linkedin Login
Renders a "Sign in with LinkedIn" button

```html
<LinkedinLogin
  apiKey="xxxxxxxxxxxxxx"
  authorize
  lang="en_US"
  onError={this.handleError}
  onSuccess={this.handleSuccess}
/>
```

#### Linkedin Add Profile
Renders a "Add to profile" button

```html
<LinkedinAddProfile
  lang="en_US"
  task="CERTIFICATION_NAME" // Or "SCHOOL_NAME"
/>
```

#### Linkedin Profile
Renders a "Member profile" card

```html
<LinkedinProfile
  lang="en_US"
  profileUrl="http://www.linkedin.com/in/praveenkumar-outlook"
  format="inline" // Or "hover"
  text="Praveenkumar K" // text to show in "hover" format
/>
```

#### Linkedin Company Profile
Renders a "Company profile" card

```html
<LinkedinCompanyProfile
  lang="en_US"
  companyId={123123123}
  format="inline" // Or "hover"
  text="Company name" // text to show in "hover" format
/>
```

#### Linkedin Share
Render a "Share" button

```html
<LinkedinShare
  apiKey="xxxxxxxxxxxxxx"
  authorize
  lang="en_US"
/>
```

## License

[MIT License](http://opensource.org/licenses/MIT)
