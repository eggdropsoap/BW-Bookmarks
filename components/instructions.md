# INSTRUCTIONS

1.  Install a TeX distribution, such as [TeX Live](https://tug.org/texlive/).
2.  Place this file in an empty directory.
3.  Place `{book}.pdf` in the same directory.
4.  Compile this LaTeX script file using the LuaLaTeX engine.  
    You can do so in a GUI TeX editor or on the command line.

    - In a GUI TeX editor: open this file, choose LuaLaTeX as the engine,
      then click "Compile" or "Typeset".
      If the editor is TeXworks or TeXShop it should read the `!TEX` command at the top of
      the file and choose the engine automatically for you when you run a compile.

    - On the command line using `lualatex` or `arara`:  
      
          lualatex {script}.tex
      
      or  

          arara {script}.tex
      
5.  The compile should result in a `{script}.pdf` file. Open the file and check
    that the bookmarks work.  
    If so, enjoy! You can rename the PDF as you like.

    If it didn't work, consider filing a bug report on this script's
    [GitHub Issues tracker](https://github.com/eggdropsoap/BW-Bookmarks/issues).
    It will help diagnose the problem if you include any output from the compile in the report.
    (If you compiled with `arara` on the command line, you'll need to re-run the compile with
    `lualatex` directly to get useful output.)
