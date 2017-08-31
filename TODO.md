# Tasks

### Configuration

1. .codacy.json **[Eddie]**
    - Add `lintr` patterns
2. Add patterns to patterns.json **[Jeanie]**
3. (Low priority) resources/docs/description/ markdown files
4. (Low priority) resources/docs/test/ .R files


### R script

1. Parse JSON blob from command line args **[Alex]**
    - Recontruct the arguments to the apply function in src/main/scala/codacy/lintr/Lintr.scala
2. Classify Files (.R and not .R)
3. Call lintr on .R files


### Create a variety of .codacy.json files to test different user configurations.

- .codacy.json will specify all tools the user is using, so for multi-language projects there will potentially be many tools and hundreds of patterns. We should do some tests like this.