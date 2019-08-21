FROM debian:9.5-slim

LABEL "com.github.action.name"="Hello World"
LABEL "com.github.actions.description"="Write arguments to the standard output"
LABEL "com.github.action.icon"="mic"
LABEL "com.github.action.color"="purple"


LABEL "repository"="http://github.com/ocotcat/hello-world"
LABEL "homepage"="http://github.com/actions"
LABEL "maintainer"="Octocat <octocat@github.com>"

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
