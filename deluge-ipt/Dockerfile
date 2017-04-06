FROM perdjesk/deluge-libtorrent:latest
LABEL org.freenas.interactive="false"                                                           \
      org.freenas.version="1.3.11"                                                              \
      org.freenas.upgradeable="false"                                                           \
      org.freenas.expose-ports-at-host="true"                                                   \
      org.freenas.autostart="true"                                                              \
      org.freenas.web-ui-protocol="http"                                                        \
      org.freenas.web-ui-port=8112                                                              \
      org.freenas.web-ui-path=""                                                                \
      org.freenas.port-mappings="8112:8112/tcp,58846:58846/tcp,6881:65534/tcp,6881:65534/udp"   \
      org.freenas.volumes="[                                                                    \
          {                                                                                     \
              \"name\": \"/config\",                                                            \
              \"descr\": \"Config storage space\"                                               \
          },                                                                                    \
          {                                                                                     \
              \"name\": \"/downloads\",                                                         \
              \"descr\": \"Downloads volume\"                                                   \
          },                                                                                    \
          {                                                                                     \
              \"name\": \"/log\",                                                               \
              \"descr\": \"Log file location\"                                                  \
          }                                                                                     \
      ]"                                                                                        \
      org.freenas.settings="[                                                                   \
          {                                                                                     \
              \"env\": \"TZ\",                                                                  \
              \"descr\": \"Timezone - eg Europe/London\",                                       \
              \"optional\": true                                                                \
          },                                                                                    \
          {                                                                                     \
              \"env\": \"PGID\",                                                                \
              \"descr\": \"GroupID\",                                                           \
              \"optional\": true                                                                \
          },                                                                                    \
          {                                                                                     \
              \"env\": \"PUID\",                                                                \
              \"descr\": \"UserID\",                                                            \
              \"optional\": true                                                                \
         }                                                                                      \
      ]"
