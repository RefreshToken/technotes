https://www.jhipster.tech/heroku/

```
./gradlew -Pprod bootWar -x test
heroku deploy:jar --jar build/libs/*war
```
