```cmd
sudo env OPENSEARCH_INITIAL_ADMIN_PASSWORD="Password@192939" apt-get install opensearch
```
```bash
curl -X GET https://localhost:9200 -u 'admin:Password@192939' --insecure
```
```
OPENSEARCH_JAVA_HOME=/usr/share/opensearch/jdk /usr/share/opensearch/plugins/opensearch-security/tools/securityadmin.sh -cd /etc/opensearch/opensearch-security/ -cacert /etc/opensearch/root-ca.pem -cert /etc/opensearch/kirk.pem -key /etc/opensearch/kirk-key.pem -icl -nhnv
```
