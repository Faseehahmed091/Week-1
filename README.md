# Week-1
I love cricket 
print('Hello,World')
print('My name is Faseeh')
print('I love cricket')
print('the program has executed')
print('the program has executed')
(venv) PS C:\Users\c7365204\PycharmProjects\pythonProject> python
Python 3.11.4 (tags/v3.11.4:d2340ef, Jun  7 2023, 05:45:37) [MSC v.1934 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> python3
Traceback (most recent call last):      
  File "<stdin>", line 1, in <module>   
NameError: name 'python3' is not defined
>>> print(the program has executed) 
  File "<stdin>", line 1
    print(the program has executed)
          ^^^^^^^^^^^
SyntaxError: invalid syntax. Perhaps you forgot a comma?
>>> print('the program has executed')
the program has executed
>>> help()

Welcome to Python 3.11's help utility!

If this is your first time using Python, you should definitely check out
the tutorial on the internet at https://docs.python.org/3.11/tutorial/.

Enter the name of any module, keyword, or topic to get help on writing
Python programs and using Python modules.  To quit this help utility and
return to the interpreter, just type "quit".

To get a list of available modules, keywords, symbols, or topics, type
"modules", "keywords", "symbols", or "topics".  Each module also comes
with a one-line summary of what it does; to list the modules whose name
or summary contain a given string such as "spam", type "modules spam".

help> 'modules' 

Please wait a moment while I gather a list of all available modules...

test_sqlite3: testing with version '2.6.0', sqlite_version '3.42.0'
C:\Users\c7365204\PycharmProjects\pythonProject\venv\Lib\site-packages\_distutils_hack\__init__.py:33: UserWarning: Setuptools is replacing distutils.
  warnings.warn("Setuptools is replacing distutils.")
__future__          _thread             getopt              sched
__hello__           _threading_local    getpass             secrets
__phello__          _tkinter            gettext             select
_abc                _tokenize           glob                selectors
_aix_support        _tracemalloc        graphlib            setuptools
_ast                _typing             gzip                shelve
_asyncio            _uuid               hashlib             shlex
_bisect             _virtualenv         heapq               shutil
_blake2             _warnings           hmac                signal
_bootsubprocess     _weakref            html                site
_bz2                _weakrefset         http                smtpd
_codecs             _winapi             idlelib             smtplib
_codecs_cn          _xxsubinterpreters  imaplib             sndhdr
_codecs_hk          _zoneinfo           imghdr              socket
_codecs_iso2022     abc                 imp                 socketserver
_codecs_jp          aifc                importlib           sqlite3
_codecs_kr          antigravity         inspect             sre_compile
_codecs_tw          argparse            io                  sre_constants
_collections        array               ipaddress           sre_parse
_collections_abc    ast                 itertools           ssl
_compat_pickle      asynchat            json                stat
_compression        asyncio             keyword             statistics
_contextvars        asyncore            lib2to3             string
_csv                atexit              linecache           stringprep
_ctypes             audioop             locale              struct
_ctypes_test        base64              logging             subprocess
_datetime           bdb                 lzma                sunau
_decimal            binascii            mailbox             symtable
_distutils_hack     bisect              mailcap             sys
_elementtree        builtins            main                sysconfig
_functools          bz2                 marshal             tabnanny
_hashlib            cProfile            math                tarfile
_heapq              calendar            mimetypes           telnetlib
_imp                cgi                 mmap                tempfile
_io                 cgitb               modulefinder        test
_json               chunk               msilib              textwrap
_locale             cmath               msvcrt              this
_lsprof             cmd                 multiprocessing     threading
_lzma               code                netrc               time
_markupbase         codecs              nntplib             timeit
_md5                codeop              nt                  tkinter
_msi                collections         ntpath              token
_multibytecodec     colorsys            nturl2path          tokenize
_multiprocessing    compileall          numbers             tomllib
_opcode             concurrent          opcode              trace
_operator           configparser        operator            traceback
_osx_support        contextlib          optparse            tracemalloc
_overlapped         contextvars         os                  tty
_pickle             copy                pathlib             turtle
_py_abc             copyreg             pdb                 turtledemo
_pydecimal          crypt               pickle              types
_pyio               csv                 pickletools         typing
_queue              ctypes              pip                 unicodedata
_random             curses              pipes               unittest
_sha1               dataclasses         pkg_resources       urllib
_sha256             datetime            pkgutil             uu
_sha3               dbm                 platform            uuid
_sha512             decimal             plistlib            venv
_signal             difflib             poplib              warnings
_sitebuiltins       dis                 posixpath           wave
_socket             distutils           pprint              weakref
_sqlite3            doctest             profile             webbrowser
_sre                email               pstats              wheel
_ssl                encodings           pty                 winreg
_stat               ensurepip           py_compile          winsound
_statistics         enum                pyclbr              wsgiref
_string             errno               pydoc               xdrlib
_strptime           faulthandler        pydoc_data          xml
_struct             filecmp             pyexpat             xmlrpc
_symtable           fileinput           queue               xxsubtype
_testbuffer         fnmatch             quopri              zipapp
_testcapi           fractions           random              zipfile
_testconsole        ftplib              re                  zipimport
_testimportmultiple functools           reprlib             zlib
_testinternalcapi   gc                  rlcompleter         zoneinfo
_testmultiphase     genericpath         runpy

Enter any module name to get more help.  Or, type "modules spam" to search
for modules whose name or summary contain the string "spam".

help>

You are now leaving help and returning to the Python interpreter.
If you want to ask for help on a particular object directly from the
interpreter, you can type "help(object)".  Executing "help('string')"
has the same effect as typing a particular string at the help> prompt.
>>> help('print') 
    Read a string from standard input.  The trailing newline is stripped.

    The prompt string, if given, is printed to standard output without a
    trailing newline before reading input.

    If the user hits EOF (*nix: Ctrl-D, Windows: Ctrl-Z+Return), raise EOFError.
    On *nix systems, readline is used if available.

>>> quit()
(venv) PS C:\Users\c7365204\PycharmProjects\pythonProject>
(venv) PS C:\Users\c7365204\PycharmProjects\pythonProject> python
Python 3.11.4 (tags/v3.11.4:d2340ef, Jun  7 2023, 05:45:37) [MSC v.1934 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> 45+20
65
>>> 10+20-15
15
>>> 10*5
50
>>> 100/3
33.333333333333336
>>> 100//33
3
>>> 10**2
100
>>> 10+5*2
20
>>> 10-5*10+5
-35
>>> 5*10**2
500
>>> (10+5)**2
225
>>> 10-5*(10+5)
-65
>>> (5*10)**2
2500
>>> 12+(5*2+3)
25
>>> 12+(5*(2+3))
37
>>> 10+
  File "<stdin>", line 1
    10+
       ^
SyntaxError: invalid syntax
>>> print('Ten divided by zero is',10/0)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ZeroDivisionError: division by zero
>>>
