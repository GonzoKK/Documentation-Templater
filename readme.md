# Documentation Templater V2

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/87bea31db9ff49609bf01043525fb510)](https://www.codacy.com/manual/James231/Documentation-Templater?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=James231/Documentation-Templater&amp;utm_campaign=Badge_Grade)

Templating engine for quickly and easily creating static web-based documentation projects. Write short and readable HTML or Markdown code containing only the important information for each page. All styling and layouts are defined in templates which can be changed to give you the full capabilities of pure HTML should you need it.

Included templates generate a clean, responsive, mobile-compatible documentation [which you can view here](https://documentation-templater-sample.jam-es.com/).

The tool is cross-platform written using .NET Core 3.1.

Features:
*   Write short documentation pages in Html or Markdown
*   Supports all the common markdown features. Add more by installing [Markdig](https://github.com/lunet-io/markdig) extensions
*   Create custom controls like `<card property="value">...</card>` similar to JS Frameworks like Anuglar and React
*   Comes with a modern and responsive example template
*   Sidebar navigation supported
*   Minifies output HTML, CSS and JavaScript for fast load times
*   Output is ready to copy into a public folder for hosting
*   Output is static so free hosting is availalbe on [GitHub Pages](https://pages.github.com/), [GitLab Pages](https://about.gitlab.com/stages-devops-lifecycle/pages/) or [Netlify](https://www.netlify.com/)
*   Very fast documentation build times which increase linearly with the number of pages

## YouTube Tutorials

[<img width="480" height="270" alt="See the First Video Tutorial on YouTube" src="https://cdn.jam-es.com/img/documentation_templater_video_thumbnail_playable.png" target="_blank"/>](https://www.youtube.com/watch?v=wbwIauMc43Y)

I am working on a series of 3 YouTube tutorials:  
- [Part 1: Downloading, Setting Up, and how to Write Content](https://www.youtube.com/watch?v=wbwIauMc43Y)
- Part 2: Changing styles/layouts or writing your own template from scratch - COMING SOON  
- Part 3: Get your documentation online for free with GitLab Pages - COMING SOON  

## Using the Tool

To use the tool, download the latest version through [GitHub Releases](https://github.com/James231/documentation-templater/releases). There are downloads for Windows, Mac and Linux, both including a bundled .NET Core 3.1 runtime, or without if you already have it installed.

[See the Wiki for a full guide.](https://github.com/James231/Documentation-Templater/wiki)

## Building from Source

To build from source you need the latest .NET Core 3 SDK. For Windows users just install the latest verion of Visual Studio 2019 with the .NET Core workload . Use the following publish command to get a single file executable:
```C#
dotnet publish -r win10-x64 -c Release -p:PublishSingleFile=true
```
where you change `win10-x64` to your platform.

There is a more detailed [guide to building from source in the Wiki](https://github.com/James231/Documentation-Templater/wiki/10.-Building-From-Source).

## License

This code is released under MIT license. Modify, distribute, sell, fork, and use this as much as you like. Both for personal and commercial use. I hold no responsibility if anything goes wrong.

If you use this, you don't need to refer to this repo, or give me any kind of credit but it would be appreciated. At least a :star: would be nice.

## Contributing

Pull requests of any form are welcome. See the [Wiki for contribution suggestions](https://github.com/James231/Documentation-Templater/wiki/11.-Welcome-Contributions).

## Support

You can contact me by submitting a contact form [here](https://jam-es.com) or by opening an issue.
