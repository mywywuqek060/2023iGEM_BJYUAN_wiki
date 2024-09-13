# Team BJYUAN-CHINA 2023 Wiki

Welcome! View our website at:

https://2023.igem.wiki/bjyuan-china/index.html

This repository contains **all** codes of our team's wiki (HTML, CSS, JavaScript, TypeScript, Python, etc).

Images, photos, icons and fonts are stored on `static.igem.wiki` using [uploads.igem.org](https://uploads.igem.org), and Videos are embedded from [iGEM Video Universe](https://video.igem.org).

reference: [competition.igem.org/deliverables/team-wiki](https://competition.igem.org/deliverables/team-wiki).

### Files

The static assets are in the `static` directory. The layout and templates are in the `wiki` directory, and the pages live in the `wiki > pages` directory.

    |__ static/             -> static assets (CSS and JavaScript files only)
    |__ wiki/               -> Main directory for the pages and layouts
        |__ footer.html     -> Footer that will appear in all the pages
        |__ layout.html     -> Main layout of your wiki. All the pages will follow its structure
        |__ menu.html       -> Menu that will appear in all the pages
        |__ pages/          -> Directory for all the pages
            |__ *.html      -> Actual pages of your wiki
    |__ .gitignore          -> Tells GitLab which files/directories should not be uploaded to the repository
    |__ .gitlab-ci.yml      -> Automated flow for building, testing and deploying your website.
    |__ LICENSE             -> License CC-by-4.0, all wikis are required to have this license - DO NOT MODIFY
    |__ README.md           -> File containing the text you are reading right now
    |__ app.py              -> Python code managing your wiki
    |__ dependencies.txt    -> Software dependencies from the Python code

### Technologies

  * [GitLab Pages](https://docs.gitlab.com/ee/user/project/pages/)
  * [Python](https://www.python.org): Programming language
  * [Flask](https://palletsprojects.com/p/flask/): Python framework
  * [Fronzen-Flask](https://pythonhosted.org/Frozen-Flask): Library that builds the wiki to be deployed as a static website
  * [Bootstrap](https://getbootstrap.com/docs/5.0/components): CSS and JS components used
