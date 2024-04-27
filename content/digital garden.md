---

---
Setting up my digital garden:

Would love to be able to use something to export my notes with something like obsidian-export, and then publish them in a more custom way than the digital garden plugin or Obsidian Publish.

Requirements:
- Automatically translate links from MD to HTML
- Show Backlinks to current document
- Able to customize what files come through based on folder, ex. all files in root, exclude folder X,Y
- Dataview integration
	- Cancels out quartz
	- Though may be able to use [dv.markdown](https://blacksmithgu.github.io/obsidian-dataview/api/code-reference/#markdown-dataviews) or [templater](https://joschua.io/posts/2023/09/01/obsidian-publish-dataview/)
- Automatic

Nice to haves:
- Show local graph

## Options
- Digital Garden Plugin
	- 
- https://linked-blog-starter.vercel.app/publish-your-obsidian-notes-with-linked-blog-starter - [YT](https://www.youtube.com/watch?v=rKSpK1dXn4E)
	- I think your notes have to be within /published, however
	- Built with Next, which would be cool to learn
- Quartz
	- https://brandonkboswell.com/blog/Publishing-your-Obsidian-Vault-Online-with-Quartz/
- Gatsby Garden
	- [Link](https://github.com/thex3family/gatsby-garden?tab=readme-ov-file) - [Example](https://notes.binnyva.com)
	- [YT Walkthrough](https://www.youtube.com/watch?v=pm0mhkWj5ac)
- Jekyll
	- [Tutorial YT](https://www.youtube.com/watch?v=kg-9n_A4Tf0) - [Link](https://github.com/maximevaillancourt/digital-garden-jekyll-template?tab=readme-ov-file)
	- This one will be lower priority, doesn't look as automated as I'd like. 


## Execution
- Full vault backup using the "Git" plugin to store in a private github repo
- Partial export of published notes using [obsidian-export](https://github.com/zoni/obsidian-export) to then publish with...? - Actually, going to try quartz first