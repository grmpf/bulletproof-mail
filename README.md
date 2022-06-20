## Mail Templates - Notes

This repository will contain basic mail head/body parts, styles required to be inlined; copy&paste styles to put in the final mail and different components to be used in mails.

> ℹ️ The markup and styles already exist, but some automation is required to remove manual steps (e.g. css inlining) and avoid mistakes.

### Main Goals
- [x] Table design html snippets (should work on "all" clients)
- [ ] Inlining some css automatically
- [ ] React components or templating system like `mustache`?
- [ ] Human-readable text-version for all components
- [ ] Website version of mails ("view email in your browser")
- [x] Send mails with node

-----

### TODOs
- [ ] Components/templates from snippets
- [ ] Add link for "view email in your browser"
- [ ] Add "hidden" mail preview text
- [ ] ...
- [ ] "Bulletproof" testing of result

-----

### Ideas
- Mail-Template
  - As Html-String (via API this should work)
  - As Plain-Text
  - (As Component)
- Text-mail:
  - Component based function (toTxt?) for simple formatting.  
  - Component based function (toTxt?) for simple formatting.
- CSS Autoprefixer possible?

-----

### Known Issues

- ...

-----

### Requirements

- next.js
- nodemailer
- ?

-----

### References

- [Litmus](https://www.litmus.com)
- [Campaign Monitor](https://www.campaignmonitor.com)
- [chromakode/react-html-email](https://github.com/chromakode/react-html-email)
- ...

-----

### Examples

- [768px screen](img/email-test-768_resized.png)
- [480px screen](img/email-test-480_resized.png)
- [320px screen](img/email-test-320_resized.png)

<table>
<tr>
<td valign="top" align="center" colspan="2">
768px screen

![768px screen](img/email-test-768_resized.png)

</td>
</tr>

<tr>
<td valign="top" align="center" width="60%">
480px screen

![480px screen](img/email-test-480_resized.png)

</td>
<td valign="top" align="center" width="40%">
320px screen

![320px screen](img/email-test-320_resized.png)

</td>
</tr>
</table>

