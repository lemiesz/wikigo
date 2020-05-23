Purpose of this project is for me to learn some Go

Basic wiki page made following the https://golang.org/doc/wiki/ tutorial.

Write now it lets you make very simple posts and view them. It saves these as text files on the server.
There are a couple optmizations I can still make to improve this

1.) Change logic to store files in /data/ folder instead of in root directory
2.) Consider adding a web framework like https://github.com/gin-gonic/gin
3.) Add mongodb integration to index the saved pages. (actually saving this data in a DB might be better overal than using text files. )
