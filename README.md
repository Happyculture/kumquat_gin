![Logo Kumquat Gin](kumquat_gin.png)

* **[Kumquat Gin](#intro)**
* **[Installation](#installation)**
* **[Patches](#patches)**
* **[Credits](#credits)**

# <a name="intro"></a>Kumquat Gin

Kumquat Gin is an administration theme based on [Gin](https://drupal.org/project/gin)
that includes some quality improvements for Kumquat based projects.

## <a name="installation"></a>Installation

- `composer require happyculture/kumquat_gin`
- Use directly or extend with your own admin theme.

## <a name="patches"></a>Patches

This theme works best with these patches:

```json
{
    "patches": {
        "drupal/paragraphs_features": {
            "[#3269941] Add paragraphs behaviors action button": "https://www.drupal.org/files/issues/2024-11-06/3269941-11.patch",
            "[#3344296] Clone remove button instead of creating a new one from scratch": "https://www.drupal.org/files/issues/2024-11-06/3344296-6.patch",
            "[#3353704] Add-in only works if active theme is claro or gin": "https://www.drupal.org/files/issues/2024-03-22/3353704-mr12-18.patch"
        }
    }
}
```

# <a name="credits"></a>Credits

The font used for the logo is [Smooth Butter from PutraCetol Studio](https://putracetol.com/product/smooth-butter/).
