# Contact point type

### Codelist:

  - contactPoint
  - attorney

### Schema:

  - ContactPoint {object}
      - type (string, null) (codelist)
      - availableLanguages (string, null)
      - languageCode (string, null)

## Defining texts:


**Code** | **Title** | **Description**
--|--|--
type | Contact point type | Specify the contact point type using the [contactPointType] () codelist.
contactPoint | Contact point | Person who serves as the point of contact for this organization.
attorney | Attorney | The attorney-in-fact is the individual who has an authorization to represent or act on another's behalf in private affairs, business, or some other legal matter.
availableLanguages | Available Language(s) | An array of language codes (e.g. en, es, uk).
languageCode | Language code | ISO language code.

