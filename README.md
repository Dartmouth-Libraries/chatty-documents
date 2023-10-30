# Chatty Documents: Large Language Models with a custom knowledge base

Large Language Models are on the rise! Are you wondering if you can somehow make them draw information from your own documents? What if you could ask it to summarize a large number of papers on a particular topic that you have gathered in your personal digital library? Or create a Q&A chat bot based on some existing documentation or manual? Wouldn’t it be cool if you could essentially have a conversation with one or more of your own documents?

In this session, we will demonstrate a few examples that let you do exactly this. We will use both OpenAI’s language models through their API, as well as an entirely local (and thus privacy-preserving) open source model. After this session, you will have a solid framework to adapt and to create your own applications!

This session is intended for users with basic knowledge of the Python programming language and the use of APIs. This session is therefore a perfect follow-up to [“Intro to Python”](https://git.dartmouth.edu/lib-digital-strategies/RDS/workshops/computational-tools/intro-to-python) and [“Let there be Data! APIs in Python”](https://git.dartmouth.edu/lib-digital-strategies/RDS/workshops/computational-tools/apis-in-python).

## Getting started

### Requirements

Some basic Python programming knowledge is required to fully understand the example code. Consider the working through [Intro to Python(https://git.dartmouth.edu/lib-digital-strategies/RDS/workshops/computational-tools/intro-to-python] prior to this workshop.

The requirements for the Python code can be installed using the following command:

```
pip install -r requirements.txt
```

### Usage

The repo has the following structure:

- `ppt`: The slide deck used in the introduction
- `docs`: An empty placeholder folder used in the examples
- `notebooks`: Notebooks illustrating the main concepts discussed in this workshop

### Issues and feedback

If you run into any trouble working with these materials, have some questions about the content, or want to give general feedback, feel free to go through one of these channels to get in touch with us:

- [Open a new issue](https://git.dartmouth.edu/lib-digital-strategies/RDS/workshops/text-analysis/chatty-documents/-/issues)
- [Send an email](mailto:simon.stone@dartmouth.edu)
- [Book an appointment](https://dartgo.org/meetwithsimon) (Dartmouth-members only)

### Licensing

<table>
<tbody>
  <tr>
    <td style="padding:0px;border-width:0px;vertical-align:center">
    Instructional materials created by Simon Stone for Dartmouth College Library under <a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons CC BY-NC 4.0 License</a>.
    </td>
    <td style="padding:0 0 0 1em;border-width:0px;vertical-align:center"><img alt="Creative Commons License" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></td>
  </tr>
</tbody>
</table>

Except where otherwise noted, the example programs are made available under the OSI-approved MIT license.




## Getting started




```
CMAKE_ARGS="-DLLAMA_METAL=on" pip install llama-cpp-python
```

[Instructions for Mac](https://github.com/abetlen/llama-cpp-python/blob/main/docs/install/macos.md)
