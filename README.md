# Chanoscope

Chanoscope is a simple Ruby CLI script to browse 4chan archives made with [BASC-Archiver](https://github.com/bibanon/BASC-Archiver). It's not perfect, but it works.

### Dependencies

- the Ruby programming language
- launchy (for cross-platform browser launching)
- nokogiri (for parsing HTML)

###Installing

Install the dependencies with `gem install`.

Put `chanoscope` in the same directory where you keep the archive directory and just run it with `./chanoscope`.

### Usage

The usage's pretty straightforward, running Chanoscope with `./chanoscope`  gives you the interactive shell.

You can also pass the board symbol, for example _diy_, as an argument.

Example:  `./chanoscope diy` selects the _diy_ board.

### Future enhancements to be done

- Generating an HTML index file
- Changing the archive path

### Contributing and forking
Please do! I'll be happy if you reference me back in some way.



