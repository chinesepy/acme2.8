# acme2.8
https://github.com/acmesh-official/acme.sh/archive/2.8.6.tar.gz

自用
把acme.sh
_ACME_CURL="curl` -L --silent --dump-header $HTTP_HEADER " 改成了
_ACME_CURL="curl -L -k --silent --dump-header $HTTP_HEADER "


配合https://github.com/andyzhshg/syno-acme
把cert-up.sh 地址改成 ACME_SH_ADDRESS=`curl -L https://raw.githubusercontent.com/chinesepyanyue/acme2.8/main/address`
