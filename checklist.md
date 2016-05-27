# README Checklist

See [README.md](README.md) to learn how to use this checklist.


## Help the reader identify the project

* **Name the file**:

  * *READMEs without markup:* Name the file `README` or `README.txt`.

  * *READMEs with markup:* Name the file `README.extension`, where
    *extension* is a file extension that corresponds to your markup language
    (such as `md` for Markdown or `rst` for reStructuredText).

* At the top of the file, **make sure the project's name is the first heading
  or plain text**.

* Under the project name or linked from it, **add a URL for the project**
  (such as repository or homepage URL).

* Under the project name, **clearly identify the owner or author of the
  project** (e.g., "By Author McAuthorface" or "Copyright Owner Name 2017").


## Help the reader evaluate the project

* **Describe the project in terms of what the project does or
  achieves**, not what it's made out of. Focus on *why* not *what*.

  *This is the hardest part of writing a README.* Try some of these Mad Libs to
  get started:

  * `With <PROJECT NAME> you can <VERB> <PLURAL NOUN>…`
  * `<PROJECT NAME> helps you _____…`
  * `If you use <PROJECT NAME> then you _____…`
  * `You'll like <PROJECT NAME> because you can _____…`
  * `<PROJECT NAME> is better than <ALTERNATIVE PROJECT> because you can
    _____…`
  * `<PROJECT NAME> is related to <OTHER PROJECT> because _____…`

  If the project is new or doesn't have an intended use, tell an origin story
  instead:

  > `One day I was _____. I tried to _____ but _____. Instead, I
  made <PROJECT NAME> to _____.`

  Or you can try inverting the description, describing what your project is
  *not* good for.

  Other tips:

  * Write to your reader in the second person (you)
  * Use action verbs and avoid the passive voice (e.g., write
    `<PROJECT NAME> creates files` instead of `Files are created by <PROJECT
    NAME>`)
  * Avoid the verbs *to be*, *to have*, and (sometimes) *to get*
  * Avoid acronyms and initialisms

  **Warning**: You may be tempted to describe how the project is made—what
               languages, technologies, and tools—instead of what the project
               does. That's sometimes useful information, but save it until
               *after* you've described how the project is supposed to help the
               reader.

* **Describe who may use the project and under what terms.**

  * *Open-source projects*:

    Describe then name the license. For example:

    > You are free to copy, modify, and distribute `<PROJECT NAME>` with
    > attribution under the terms of the MIT license. See the `LICENSE` file
    > for details.

    For inspiration for talking about licenses, see the Creative Commons
    human-readable license summaries, such as
    [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).

  * *Closed-source projects*:

    Describe who may use and distribute the project. For publicly available
    projects, you may reference an EULA or other licensing document.

    For private or internal projects, you may want to explicitly allow or deny
    public disclosure of the project. For example:

    > You may only use `<PROJECT NAME>` for internal BigCorp projects.


## Help the reader use the project

* If applicable, **list the project's prerequisites**.

  Your project may require things that are out of the scope of ordinary
  installation or usage instructions. List these requirements before or at the
  beginning of such instructions. For example, you may require a version of
  Python, but you don't need to include instructions for how to install it.

  For example:

  > Before installing `<PROJECT NAME>` you need:
  >
  > * Git
  > * Python 2.7 or later

  If you're feeling especially generous, link to those projects' setup
  instructions or websites.

* **List the steps to install and use the project one time.**

  Help the reader go from having your project's files to using the project for
  the first time. For a programming language, this might be installation
  followed by running a "hello world" program. For a documentation project this
  might be building the site and opening the homepage in a web browser. For a
  README-only project, this might be a preface or introduction.

  No matter how your project runs, however, stop once the project works once.
  Extended usage instructions belong in dedicated documentation files, not
  your README.

* **Test your install and setup steps.**

  There's nothing to write down for this, but be sure what you've already
  written actually works.


## Help the reader engage with the project

* **Tell your audience where to go for more project documentation.**

  Describe any additional documentation and where to find it.

  This may include your project's:

  * Website
  * Documentation files
  * Man page
  * Help command(s)
  * top-level README companion files, such as `LICENSE`, `CONTRIBUTING`,
    `CODE_OF_CONDUCT`, `AUTHORS`, `CHANGELOG`, and `BUGS`.

  It's not enough to link to documents; briefly describe them too.

* **Tell your audience where to go for help.**

  This may include descriptions and links to mailing lists, issue trackers,
  forums, email addresses, or other support avenues (like Stack Overflow tags).

  If the project is unsupported or support is only available for a fee, now
  would be a good time to mention that.

* **Tell your audience how to help.**

  * *Open-source projects*: link to and summarize the project's contributor's
    guide, if one exists, or describe how and where you want contributors to
    add to your project (e.g., via GitHub pull requests or patches mailed
    to a specific address).

    *See also*: [nayafia/contributing-template](
    https://github.com/nayafia/contributing-template/)

  * *Closed-source projects*: describe how and where bugs should be reported.

## Final checks

* **If your README is long, add a table of contents** after your project
  description.

  If your README is more than three or four screens long, make it easier to
  skim by adding a table of contents. A list of section headings is enough.

* **If your README is very long, move content to other documents.**

  If your README is more than ten or twelve screens long, move stuff into
  separate documents. Keep your README file short, or readers may become
  overwhelmed. A comprehensive README is a bad README.

  Topics not covered by this checklist are likely candidates for becoming
  separate documents. For example, version histories can be moved to a
  `CHANGELOG` or `RELEASES` file and replaced with a link to the new file.

* **Set a reminder to review your README and this checklist in a few weeks**.
