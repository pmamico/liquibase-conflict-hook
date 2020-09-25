### Story

Detecting database changes in different git branches and alert on conflict (changing same database table).

### Requirements

- git
- liquibase changes in xml format
- xmllint
- git-flow ( "feature/" grep in code, feel free to change it)

### Usage

Copy the post-commit file into your projects $GIT_DIR/.git/hooks/post-commit.