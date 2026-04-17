```
GRETL_IMAGE_TAG=3.2 docker compose run --rm -u $UID --workdir //home/gradle/schema-jobs/shared/schema \
gretl -PtopicName=awa_energieberater -PschemaDirName=schema createSchema configureSchema
```