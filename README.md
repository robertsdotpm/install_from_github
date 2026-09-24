# Sample projects

Small "hello" programs, one per language, for trying out installers and
build tooling. Each prints a line and exits.

At the top level, because their files do not collide and each runs from
the root of a checkout:

| Language | Run it with |
| --- | --- |
| Python | `python -m hello` |
| Node.js | `node index.js` |
| Ruby | `ruby hello.rb` |
| PHP | `php index.php` |
| R | `Rscript main.R` |
| Java | `javac Hello.java && java -cp . Hello` |

In their own directories, because each brings a build file that would
confuse the others in a shared one:

| Language | Directory |
| --- | --- |
| Python 2 | `python2/` |
| .NET | `dotnet/` |
| Go | `go/` |
| Rust | `rust/` |
| Zig | `zig/` |
| Nim | `nim/` |
| C | `cc/` |

There is nothing else here. They are deliberately as small as a working
program in each language can be.
