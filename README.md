# neos-getting-started

[![Contact me on Codementor](https://cdn.codementor.io/badges/contact_me_github.svg)](https://www.codementor.io/amappuji?utm_source=github&utm_medium=button&utm_term=amappuji&utm_campaign=github)
[![Made in Indonesia](https://img.shields.io/badge/made%20in-indonesia-red?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAAAXNSR0IArs4c6QAAAIRlWElmTU0AKgAAAAgABQESAAMAAAABAAEAAAEaAAUAAAABAAAASgEbAAUAAAABAAAAUgEoAAMAAAABAAIAAIdpAAQAAAABAAAAWgAAAAAAAABgAAAAAQAAAGAAAAABAAOgAQADAAAAAQABAACgAgAEAAAAAQAAAA6gAwAEAAAAAQAAAA4AAAAAoZe4PgAAAAlwSFlzAAAOxAAADsQBlSsOGwAAAVlpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IlhNUCBDb3JlIDUuNC4wIj4KICAgPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4KICAgICAgPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIKICAgICAgICAgICAgeG1sbnM6dGlmZj0iaHR0cDovL25zLmFkb2JlLmNvbS90aWZmLzEuMC8iPgogICAgICAgICA8dGlmZjpPcmllbnRhdGlvbj4xPC90aWZmOk9yaWVudGF0aW9uPgogICAgICA8L3JkZjpEZXNjcmlwdGlvbj4KICAgPC9yZGY6UkRGPgo8L3g6eG1wbWV0YT4KTMInWQAAAf9JREFUKBV9Ur9PFFEQnvdjd8+DUwv0YrJhQ454PZXFAbEzdDZWZ2FiZcGfQ3Wdl1jQWF1FMBI0FrRG74LIhuM8chAIgd3bfbvznFnwIkad5Nt9b+Z9876ZeQIABMESyoSAgIS/mSRnSIgIgknwFGB5cWWl/bDR8F2lcoEoxVUIrLVgpcQsz1Vve7v/odNprgO818QrP6rX2y9XV/3K7KyBLHM42XVO0sJiQIHWZmlhwc92v7XXe906E4O5Ws13u12DOzuSbsMJiSlsTJZSepWKqc3XfOh1Ayai+h7m+eam42mNVggprm4pOAWPPlQTWlLjhmHOHCaC/fJZiv09gDjm7T9NOA5IY+QMndBzlRmw8wFg9R7tKM8ft02yULMsVWFHx1D5ugfaffwE7ItnYJcbAFNTADkpue7ohMT9UTSNNAX4+Anc1hvQqecCeB7ALRqjS+v/mFUarEtnySQfRZMhZqZwFHJIbjG/X3+SyIaGppWmyFRZLZVklCQqHifMpFlLpOHfAPs4dhHH5vwyUvfvlKTcer0W/jga9Ycnp87x6RnGSSJT6pzJsgK8HpOPY4ejE+dgMOxvtN6GPI5of3DU7Gy8a/sPqv7t6enc0erGk6PnhucXlwXp4HDYBBhE1GMrqIvct/LS81fB2XiMCW1+N67pLsnbaq0Vj5zqFz8BHc350tk1bDEAAAAASUVORK5CYII=)](https://github.com/made-in-indonesia/made-in-indonesia)

Try to get NEOS CMS running on local.

## How to run

* Install composer

    ```bash
    curl -sS https://getcomposer.org/installer | php
    ```

* Using composer command

    ```bash
    php composer.phar <command>
    ```

* Install composer package

    ```bash
    composer install
    ```

* Run the docker-compose

    ```bash
    docker-compose up -d
    ```
  
* Run the server

    ```bash
    ./flow server:run
    ```

* Open the setup page on http://localhost:8081
* This is the database credentials

    ```
    username: postgres
    password: postgres
    host: 127.0.0.1
    ```
