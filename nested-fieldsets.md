# Nested fieldset

It is possible to nest a fieldset inside another fieldset. Although it is valid markup, screen readers do not automatically indicate the end of a fieldset which can make if difficult for users to confidently know which fields belong to which fieldset.

## Audit template

### Description

**Issue:** Nested fieldsets

**Page:**

**URL:** 

**Description:** This page contains one or more fieldsets that are nested inside another fieldset. Although this is valid markup, screen readers do not automatically indicate the end of a fieldset which can make if difficult for users to confidently know which fields belong to which fieldset.

**Resolve:** Structure the questions on the page in such a way that nested is not required, if the page is complex then consider spilting the page into multiple smaller, less complex, pages.

### Labels

* design pattern
* usability
* fieldset

## WCAG violation summary

| Priority | Issue | Fix verified |
| -------- | ----- | ------------ |
| 🟠 2     | #[issue]: Nested fieldsets | |

## References

[Fieldset - GOV.UK Design System](https://design-system.service.gov.uk/components/fieldset/)

[Using the fieldset and legend elements - GOV.UK blog post](https://accessibility.blog.gov.uk/2016/07/22/using-the-fieldset-and-legend-elements/)
