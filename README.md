# OpenMetadata Test Run

After building the images and starting the system via

```bash
docker compose up --build
```

the UI can be accessed at [http://localhost:8585](http://localhost:8585) and you can log in with

* username: admin
* password: admin

In production, you can configure [better security](https://docs.open-metadata.org/deployment/security/basic-auth).

I also added my `.env` file to this repo, but in anything real, put `.env` in a `.gitignore` file (and also don't do `git add .`; add things intentionally).

# Interfaces

## Landing Page

[](imgs/landing_page_dashboard.PNG)

## Explore Tab

[](imgs/explore_page.PNG)

## Quality Tab

You can add quality checks.

[](imgs/quality_tab_landing_page.PNG)

[](imgs/quality_tab_add_testing_suite.PNG)

## Insights Tab

[](imgs/insights_landing_page_data_assets.PNG)


## Govern Tab

[](imgs/govern_tab_glossary_landing_page.PNG)
[](imgs/govern_tab_add_glossery_form.PNG)
[](/imgs/govern_tab_tags_landing_page.PNG)
[](imgs/govern_tab_tags_Tier_category.PNG)         
[](imgs/govern_tab_tags_PII_category.PNG)

## Settings Tab

[](imgs/settings_page.PNG)
[](imgs/settings_add_pipeline_service_interface.PNG)
[](imgs/settings_add_dashboard_service_interface.PNG)
[](imgs/settings_add_database_interface.PNG)
[](imgs/settings_add_messaging_service_interface.PNG)
[](imgs/settings_add_ML_model_service_interface.PNG)

### Access Control
[](imgs/settings_default_access_control_policies.PNG)
[](imgs/settings_default_access_control_roles.PNG)