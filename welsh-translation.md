# Welsh translations

## Audit template

### Description

**Issue:** Content not translated to Welsh

**WCAG 2.1 failure:** 3.1.2: Language of Parts - https://www.w3.org/WAI/WCAG21/Understanding/language-of-parts.html

**Page:**

**URL:**

**Description:** When switching the language of the page to Welsh some parts remain as English and are not marked up with the appropriate language attribute to differentiate them from the other content.

* the skip link is not translated

**Resolve:** 

* the skip link is currently hard-coded as English in the Gov template in play-frontend-govuk
However it is possible to send an ovverride skip link to the @skipLinkBlock code block and with that send the correct translation. If doing this you should ensure you use the skip link component (as the template does) rather than developing your own version.

### Labels

* wcag
* wcag 3.1.2 (AA)
* welsh language toggle

## WCAG violation summary

| Status | Level | Issue | Success Criterion |
| ------ | ----- | ----- | ----------------- |
| 🟠 (M) | AA    | #[issue]: Content not translated to Welsh | 3.1.2 Language of parts |
