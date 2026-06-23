# eduroam Android Profile Outer Identity Map

This repository contains a static website and markdown report for a profile-level analysis of Android eduroam `eap-config` profiles.

## Website

Open `index.html` or visit the GitHub Pages site after deployment.

The map visualizes the country-level percentage of profiles that do **not** explicitly contain an `OuterIdentity` or `AnonymousIdentity` field.

## Included datasets

- geteduroam discovery verified-university subset
- CAT User API university-matched subset

## Report

See:

- `report/README.md`
- `report/geteduroam_country_school_lists.md`
- `report/cat_country_school_lists.md`

## Method note

This is profile-level analysis only. A missing outer identity field means the downloaded profile does not explicitly configure `OuterIdentity` or `AnonymousIdentity`. It does not directly prove runtime username exposure.
