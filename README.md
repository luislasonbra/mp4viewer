MP4Viewer
=========

MP4Viewer is an ISO base media file format viewer. It parses the isobmf file and displays the metadata on the console or in a separate window. The definitions of structures used in the code can be found in the publicly available standard [ISO/IEC 14496-12 - ISO base media file format](http://standards.iso.org/ittf/PubliclyAvailableStandards/index.html)

Usage: cd into `src` folder and run

    $ ./showboxes.py [-h] [-o {stdout,gui}] [-c {on,off}] iso-base-media-file

    Positional arguments:
      iso-base-media-file   Path to iso media file

    Optional arguments:
      -o {stdout,gui}       Select output format (console or windows)
                            TODO: Add XML output
      -c {on,off}           Turn on/off colors in stdout; on by default.
      -h, --help            Help!

MP4Viewer uses gtk in graphics mode and requires that pygtk2.0 be installed in the system for viewing results in a window.

For more info, contact the author at amarghosh at gmail dot com
