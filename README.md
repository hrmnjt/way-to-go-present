# Presentations in code

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/hrmnjt/way-to-go-present)

Are you bored of powerpoints and want to make slide that get the content correct. You can use go.talks/present tool to create slides that look great and simple and lets you focus on the content. All that with minimal effort while maintaining content with code and version control.

This project serves as a base for your presentation.

## Usage

### Build and run your content locally:

1. Install go.talks/present
2. Create some_content.slide in your editor
3. Run the tool $GOPATH/bin/present

View the content of the .slide file on the browser @ localhost:3999
__You can check the format of content from example.slide in this repo__

### Host your content globally:

1. Commit and push your .slide to your public Github/Gitlab repository
2. Go to https://talks.godoc.org/github.com/YOUR_USER_NAME/YOUR_REPOSITORY_NAME/PATH/TO/SLIDE.slide to share and view your slide

For example slide and tutorial - https://talks.godoc.org/github.com/hrmnjt/way-to-go-present/example.slide

## References

Official documentation - https://godoc.org/golang.org/x/tools/present  
Example content - https://talks.golang.org/2017

## Comments

Please create an issue if there are any comments. Constructive criticism is appreciated!

## License

```
Copyright 2020 hrmnjt

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
