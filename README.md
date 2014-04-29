Sublime Text Snippets For pytest
===========================================

Sublime Text snippets for testing with [pytest](http://pytest.org/latest/).

Install
-------

### Package Control (the easy way)


Install Sublime Package Control if you don't have it.

In the command pallette (Cmd-Shift+P on Mac) type 'Install' then press enter to see a list of packages. Search for 'pytest snippets' then press enter to install.

### ...OR copy files to your Packages directory.


#### Mac OS X
    git clone git://github.com/sloria/sublime-pytest-snippets.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/Python/sublime-pytest-snippets

#### Windows
    git clone git://github.com/sloria/sublime-pytest-snippets.git %userprofile%\AppData\Roaming\Sublime Text 3\Packages\Python\sublime-pytest-snippets


Examples
--------

- `a==` expands to `assert first == second`
- `a>` expands to `assert first > second`
- `fixture` expands to 

```python
@pytest.fixture(scope='function')
def name:
    body
```

All snippets
------------

Assertions

- `a==` and `a!=`
- `a~=` and `a!~=`
- `a>`, `a>=`, `a<`, and `a<=`
- `atrue` and `afalse`
- `ain` and `a!in`
- `ais` and `aisnot`
- `araises`

Fixtures

- `fixture`
- `yieldfixture`
- `mark`
- `parametrize`

License
-------

Licensed under the [WTFPL](http://www.wtfpl.net/).
