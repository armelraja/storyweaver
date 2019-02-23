# About StoryWeaver

StoryWeaver, an initiative from Pratham Books, is designed to provide children with reading resources.
StoryWeaver is a digital gateway to thousands of richly illustrated, open-licensed children's stories in mother tongue languages.

# Problem Statement

Using language processing techniques, analyse how the complexity of language changes across levels of the story.


# DataSet

The dataset (under the `data` folder) provided contain datadump from StoryWeaver.

It contains original and translated stories in English, Telugu and Hindi languages.

## Column Description
'story_id','title',english_title	reading_level_updated	story_langugage	synopsis	content	category_name	tag_name	story_original_title

| **Column**            | **Description**   |
| --------------------- |:-------------:|
| story_id              | Identifier of the story |
| title                 | Title of the story
| english_title         | TItile of the Story in english      |
| reading_level_updated | Reading complexity of the book      |
| story_langugage       | Language of the story content              |
| synopsis              | Short description of the Story              |
| content               | Story content               |
| category_name         | Comma separated values of the story categories             |
| tag_name              | Comma separated values of the story tags(if any)              |
| story_original_title  | Title of the original story if translated. Same as the title of the original story.               |
