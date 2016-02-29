#How change timezone
####Remove the locatime information
`$ rm -f /etc/localtime`
####Add personal locatime
`$ ln -s /usr/share/zoneinfo/America/Sao_Paulo /etc/localtime`
