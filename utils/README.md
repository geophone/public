-- Utils
a) ppush
    Explain: 
        You know I can't be fucked with to calculate my pushes and push incrementally and all this crap
        Furthermore I work with a lot of AI repos which can pull in large models which you probably don't need on git for the sort of IP value, although if you have something heavily trained you do want to save it. 
        Most will not disappear from the internet as regards IP
    Usage:
        After you do git add * && git commit -m 'dgaf' 
        just run 'ppush' this will skip all files in the commit >10MB and add them to .gitignore
        then it will batch the remaining files as they fit into ARG_MAX and <500MB this is just for practicality github has like a 2GB limit on a push pack and bitbucket 2.5GB imho these are WAYYYYY too low especially considering LFS

