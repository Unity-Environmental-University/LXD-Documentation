# Familiarizing with the Writerside File Structure

## Overview
Understanding the file structure in JetBrains Writerside is crucial for efficient document management and navigation. This guide provides an overview of the typical file structure and best practices for organizing your documentation projects.

## Best Practices for File Organization

<!--Here's some xml mixed with markdown for mixed use example-->
### Project Files
The main places to familiarize yourself with are the "topics" and "images" folders. Topics are automatically added
to the "topics" folder. When adding images, be sure to keep them organized.

<img src="images_topics.png" alt="Image of the File Structure. The 'Images' and 'Topics' tabs focused" 
height="400"/>

>While images don't need to be placed in the images folder, continuity will help overall.

### Consistent Naming
- Use clear and descriptive file names.
- Follow a naming convention, like `TopicName-Subtopic.md`.
>Be sure to _**avoid spaces**_ when naming files, as they don't play nice with xml & markdown
> Example: Use `file_name` rather than ~~`file name`~~
>{style=warning}
---

### Default file types

.md files
: `topic.md` files are markdown files. They can still use xml, but they start out as markdown files

.topic files
: `topic.topic` files are xml files. They cannot use markdown.

---

## Working with the File Structure

### Creating Files and Folders
- Right-click in the Project Explorer and select `New > File` or `New > Directory`. 

_OR_

- From the 'Writerside' tab, we can click the `+ > Empty MD Topic`
  ![Create new topic options](new_topic_options.png){ border-effect="line" thumbnail="true" width="400"}

### Renaming and Moving Files
- Right-click on a file or folder and select `Rename` or `Move`.
    - If not available, try `Refactor > Rename`

### Deleting Unnecessary Files
- Right-click and select `Delete` to remove files or folders.

## Conclusion

Understanding and effectively organizing the file structure in JetBrains Writerside will enhance your documentation workflow and ensure easy navigation and maintenance of your project.

## Additional Resources
- [JetBrains Writerside Documentation](https://www.jetbrains.com/help/writerside/discover-writerside.html)
- [Markdown Syntax Guide](https://www.markdownguide.org/basic-syntax/)
- [XML Syntax Guide](https://www.w3schools.com/xml/xml_syntax.asp)
