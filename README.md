# Engineering Notebook

### Things I Believe About Software Engineering
- [Things I Believe About Software Engineering — Wesley Aptekar-Cassels](https://blog.wesleyac.com/posts/engineering-beliefs)
- [Things I believe — stettix](https://gist.github.com/stettix/5bb2d99e50fdbbd15dd9622837d14e2b)


### Reproducible Excel Build with Openpyxl 
- workbook.properties.modified and workbook.properties.created datetime set when creating and modifying an Excel  
- workbook.properties.modified overwrite as the last thing before saving
- To create a reproducible Excel file, Workbook subclass that doesn't set the modified datetime is need
- [whois-server-list PR#17](https://github.com/RamVasuthevan/whois-server-list/pull/17) 

## Metabase
 - Got my personal instance working. DO Docker instance + AWS RDS Postgres. Need to setup ngnix. 
 - TODO: write article