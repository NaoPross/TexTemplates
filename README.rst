(Xe)LaTeX Templates
:::::::::::::::::::

This is a mirror of what I keep under ``~/templates/tex`` on my computer.
Most LaTeX installs should come with the packages required to build this.
For manual installs or TinyTex, ``packages.txt`` contains a list of packages
that I had on my machine when I made these templates::
    
    tlmgr list --only-installed | awk 'gsub(/:/,"") {print $2}' > packages.txt
    cat packages.txt | xargs tlmgr install
