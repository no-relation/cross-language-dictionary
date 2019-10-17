<!--
Ruby | Javascript | Python
:---:|:---:|:---:
-->

# String Interpolation or Template Literals

|        Ruby        |       Javascript       |                      Python                      |                                    C#                                    |
| :----------------: | :--------------------: | :----------------------------------------------: | :----------------------------------------------------------------------: |
| `"string #{code}"` | `` `string ${code}` `` |              `'string %s' %(code)`               | `"string {0} {1}", code at {0}, code at {1}` <br/> OR `$"string {code}"` |
|   double quotes    |     grave accents      |            (v3.6) `f'string {code}'`             |                                                                          |
|                    |                        | `'string {stringCode}'.format(stringCode=code)`) |

# Array functions

|                    Ruby                     |                 Javascript                  |                Python                |                        C#                        |
| :-----------------------------------------: | :-----------------------------------------: | :----------------------------------: | :----------------------------------------------: |
| `object.method { \|item\| item.something }` | `Array.method( (item) => item.something );` |                                      |                  requires LINQ                   |
|                   `each`                    |                 `forEach()`                 |         `for item in list:`          |            `foreach item in list {}`             |
|              `map` / `collect`              |                   `map()`                   |  `list(map(function, input_list))`   |       `array.Select(x => operation on x)`        |
|                  `select`                   |                 `filter()`                  | `list(filter(function, input_list))` |      `array.Where(x => boolean operation)`       |
|                   `first`                   |                  `find()`                   |                `???`                 |
|                    `sum`                    |                 `reduce()`                  | `list(reduce(function, input_list))` | `array.Aggregate((x,y) => operation on x and y)` |
|          `array.join("separator")`          |          `array.join("separator")`          |       `"separator".join(list)`       |        `string.Join("separator", array)`         |

# String functions

|     Ruby     |   Javascript    |     Python     |     C#      |
| :----------: | :-------------: | :------------: | :---------: |
| `capitalize` |      none       | `capitalize()` |    none     |
|   `upcase`   | `toUpperCase()` |   `upper()`    | `ToUpper()` |
|  `downcase`  | `toLowerCase()` |   `lower()`    | `ToLower()` |
|   `strip`    |    `trim()`     |   `strip()`    |  `Trim()`   |

# Number functions

|       Ruby        | Javascript |     Python     |            C#             |
| :---------------: | :--------: | :------------: | :-----------------------: |
| `Float::Infinity` | `Infinity` | `float("inf")` | `double.PositiveInfinity` |

<!--
# Loops
Ruby | Javascript | Python
:---:|:---:|:---:
  -->

# Exception handling

|             Ruby              |               Javascript               |                Python                 |                   C#                   |
| :---------------------------: | :------------------------------------: | :-----------------------------------: | :------------------------------------: |
| `begin rescue {raise} ensure` | `try {} catch(err) {throw} finally {}` | `try except someError: raise finally` | `try {} catch(err) {throw} finally {}` |

# Terminal Output

|  Ruby  |  Javascript   |  Python   |         C#          |
| :----: | :-----------: | :-------: | :-----------------: |
| `puts` | `console.log` | `print()` | `Console.WriteLine` |

# Code Comments

|                         Ruby                         |           Javascript           |                               Python                               |               C#               |
| :--------------------------------------------------: | :----------------------------: | :----------------------------------------------------------------: | :----------------------------: |
|                   `# single line`                    |        `// single line`        |                          `# single line`                           |        `// single line`        |
| `=begin` <br/> `multiple` <br/> `lines` <br/> `=end` | `/* multiple` <br/> `lines */` | `"""multiple` <br/> `lines"""` <br/> (actually a mulitline string) | `/* multiple` <br/> `lines */` |

# Data Types

|            example             |         Ruby          |    Javascript     |            Python             |      C#       |
| :----------------------------: | :-------------------: | :---------------: | :---------------------------: | :-----------: |
|                                |         `nil`         |      `null`       |            `None`             |    `null`     |
|       `[value1, value2]`       |         array         |       array       |             list              | array or list |
| `{key1: value1, key2: value2}` |         hash          |      object       |          dictionary           |  dictionary   |
|             truthy             | `0`, `""`, `[]`, `{}` |    `[]`, `{}`     |              ??               |    `true`     |
|             falsy              |         `nil`         | `null`, `0`, `""` | `None`, `0`, `""`, `[]`, `{}` |    `false`    |

# External Libraries

|                         |            Ruby            |                     Javascript                     |                    Python                     |          C#          |
| :---------------------: | :------------------------: | :------------------------------------------------: | :-------------------------------------------: | :------------------: |
|  package <br/> manager  |        rubygems.org        |                    npm or yarn                     |                   pypi.org                    |        NuGet         |
|  install <br/>command   |       `gem install`        |                   `npm install`                    | `pip install` OR <br/>`pip3 install` on POSIX | `dotnet add package` |
| include <br/> statement | `gem pkgname` (in gemfile) | `import pkgname` OR `import function from pkgname` |        `from pkgname import function`         |   `using pkgname`    |
