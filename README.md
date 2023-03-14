# MCQs

This is a repository containing questions.

The format is as follows:

- Go to the `content` folder
- Create one subfolder per multiple choice question
	- The name should use alphanumeric characters
	- For organization, we recommend to use a number followed by a dot and a slug
- Inside that subfolder please include the following files
	- index.md (containing the question)
	- 1.correct.md, 2.correct.md, etc (as many correct options as you would like)
	- 3.md, 4.md, 5.md, etc (as many incorrect options as you would like)

This format allows you to use Markdown in the questions and options, including pieces of code. Feel free to use emojis, tables or any valid Markdown you like.

The system will take care of showing the options in random order, per exam. So for example one student may see:

- [ ] Option 3
- [ ] Option 4
- [ ] Option 1
- [ ] Option 5
- [ ] Option 2

... while other will get:

- [ ] Option 2
- [ ] Option 3
- [ ] Option 1
- [ ] Option 5
- [ ] Option 4
