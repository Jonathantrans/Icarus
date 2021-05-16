Welcome to Jonathan Trans's Project: Icarus. \
We are excited to see you here! 😊 

Icarus is a tool and platform to analyze pictures of patients who are concerned about skin cancer, acne, and other dermatology problems, detecting whether or not they have it and the spread of the skin problem if they do. We, at Icarus, want to bring out a new product to the public for social good through machine learning and introduce an easier way to interact with dermatologist. This project has yet been released to the public and is expected to release fall 2021.

Tools: HTML, CSS, React Native, Swift, C++, Git/Github, Python (Matplotlib, PyTorch, Pandas, Tensorflow), and more to be added...👻

# Link(s) : 
LinkedIn: https://www.linkedin.com/in/jonathantrans/ \
Personal Website: https://jonathantrans.github.io/ \
Icarus: TBA

Icarus 😎
=================

PDF and HTML versions of this guide are available at the [PreTeXt](https://pretextbook.org) site in the Documentation area.

If you wish to build from source, possibly as part of contributing improvements, follow these steps:

1.  To build LaTeX for input to `pdflatex`:
        cd /path/to/mathbook
        xsltproc -xinclude -o guide.tex xsl/pretext-latex.xsl doc/guide/guide.xml
1.  And for HTML output:
        cd /path/to/mathbook
        xsltproc -xinclude xsl/pretext-html.xsl doc/guide/guide.xml
1.  You might prefer to set your default directory to someplace outside the PreTeXt distribution and include full paths to the XSL and XML files in the `xsltproc` command, so your output is not mixed in with your source.
1.  Note, we do not include directions here for the multiple steps necessary to have the WeBWorK examples built correctly.  You will get an error message, but the rest of your ouput should not be affected.

If you are contributing new material, note that there are three important elements in use.  Please make use of them in your contribution.
* `tag` - for element names
* `tage` - for names of empty elements
* `attribute` - for names of attributes
