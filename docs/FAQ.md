# Frequently Asked Questions

**Integration**
[OK, I've downloaded the library. Now what ? Where do I start ?](#FAQI.1)
[I'm not interested in contributing to ATL and I need the XXX feature for my app. When will the XXX feature be implemented ?](#FAQI.2)
[Is there any way to see ATL in action on a specific music collection before integrating the library ?](#FAQI.3)

**Development**
[What are Dummy classes used for ?](#FAQD.1)
[Really, some sections of the code could be better if XXX](#FAQD.3)

**Misc.**
[Help ! I don't know anything about programming, I just want to read XXX data from my audio files and write it into a list](#FAQM.1)


## Integration

{anchor:FAQI.1}
**OK, I've downloaded the library. Now what ? Where do I start ?**

You might want to read the [Usage / Code snippets](Usage-_-Code-snippets) section of the documentation to get started with using ATL in your project.

{anchor:FAQI.2}
**I'm not interested in contributing to ATL and I need the XXX feature for my app. When will the XXX feature be implemented ?**

You are welcome to use [the Discussions area](https://atldotnet.codeplex.com/discussions) to suggest and discuss new features.

{anchor:FAQI.3}
**Is there any way to see ATL in action on a specific music collection before integrating the library ?**

I'm maintaining a fully native C# application called [Ethos Cataloger](https://trello.com/b/ZAzRjbXZ/ethos-cataloger), which is based on the latest version of ATL .NET. You're welcome to download it, scan your own audio files and even export the results on multiple output formats.


## Development

{anchor:FAQD.1}
**What are Dummy classes used for ?**

DummyReader and DummyTag are used whenever ATL does not know how to read data (e.g. no parsable metadata in DTS files / trying to read an unsupported audio format with ATL)


{anchor:FAQD.3}
**Really, some sections of the code could be better if XXX**

ATL .NET is a project I'm maintaining during my free time, with the knowledge I've acquired by personal research on C#/.NET features and digital audio. I know it's not perfect, but it reaches its primary goal, i.e. scanning thousands of tracks from my music library in a matter of seconds.

Anyway, you're welcome to fork and submit any improvement, or discuss design and implementation choices on [the Discussions area](https://atldotnet.codeplex.com/discussions).


## Misc.

{anchor:FAQM.1}
**Help ! I don't know anything about programming, I just want to read XXX data from my audio files and write it into a list**

You might be interested in using [Ethos Cataloger](https://trello.com/b/ZAzRjbXZ/ethos-cataloger), which is based on the latest version of ATL .NET. You're welcome to download it, scan your own audio files and export the results on multiple output formats.
