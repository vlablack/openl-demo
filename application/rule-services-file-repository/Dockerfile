FROM  openltablets/ws:5.23.10

RUN groupadd  -r demo && useradd -m -g demo demo

COPY target/classes/application.properties webapps/ROOT/WEB-INF/classes

COPY target/openl-repository/ /home/demo/openl-repository/
