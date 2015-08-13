---
layout: post
title:  "gcc upgrade error Mac OS X 10.6.8"
date:   2015-08-13 08:19:40
categories: gcc OSdownshifting
---
==> Upgrading 1 outdated package, with result:
gcc 5.2.0
==> Upgrading gcc
==> Downloading http://ftpmirror.gnu.org/gcc/gcc-5.2.0/gcc-5.2.0.tar.bz2
Already downloaded: /Library/Caches/Homebrew/gcc-5.2.0.tar.bz2
==> Patching
patching file gcc/jit/Make-lang.in
==> ../configure --build=x86_64-apple-darwin10.8.0 --prefix=/usr/local/Cellar/gcc/5.2.0 --libdir=/usr/local/Cellar/gcc/5.2.0/lib/gcc/5 --enable-langu
==> make bootstrap
Bootstrap comparison failure!
gcc/host-darwin.o differs
make[2]: *** [compare] Error 1
make[1]: *** [stage3-bubble] Error 2
make: *** [bootstrap] Error 2

READ THIS: https://git.io/brew-troubleshooting

These open issues may also help:
apple-gcc42 takes priority over modern gcc https://github.com/Homebrew/homebrew/issues/41055
gcc 4.9.2 fails to produce debugging information https://github.com/Homebrew/homebrew/issues/34976
Object files deleted during build of gcc needed by gdb https://github.com/Homebrew/homebrew/issues/35734
MacOS.(gcc|clang|llvm)_version can return nil https://github.com/Homebrew/homebrew/issues/18781

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

UPDATE
Markdown Github additions:

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> are supported
  - [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

* SHA: a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User@SHA: jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User/Repository@SHA: jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* #Num: #26
* GH-Num: GH-26
* User#Num: jlord#26
* User/Repository#Num: jlord/sheetsee.js#26

More on this look at [github flavored markdown][fm]

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
[fm]:          https://help.github.com/articles/github-flavored-markdown/