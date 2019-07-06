# visitor-count-badge
A badge generator for count visitor of your README

## Demo
See below badge, try to refresh current page then see again :tada:

[![](https://visitor-count-badge.herokuapp.com/total.svg?repo_id=jwenjian.visitor-count-badge)](https://github.com/jwenjian/ghiblog/issues/43)

## Install dependencies

1. `pip install -U Flask`
2. `pip install pybadges`

## How to use

Add a image to your README file:

```markdown
![Total visitor](https://visitor-count-badge.herokuapp.com/total.svg?repo_id=#{put your repo_id here, see below for detail})
```

repo_id: 

An unique string represent your current README, recommend as following pattern

- For README:

{your.github.login}.{your.repo.id}

- For Issue:

{repo.owner.login}.{repo.id}.issue.{your.issue.id}
