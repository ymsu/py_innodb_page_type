# py_innodb_page_type
Parse InnoDB table page type
- forked from jameslcj/david-mysql-tools
- Automatically exported from code.google.com/p/david-mysql-tools

---
### Create a symbolic link for global usage
1. Grant executable permission
   ```shell
   chmod +x py_innodb_page_info.py  
2. create symbolic link
   ```shell
   ln -s /opt/soft/mysql_tools/py_innodb_page_type/py_innodb_page_info.py /usr/local/bin/py_innodb_page_info
3. Now you can execute py_innodb_page_info from any location in the system
   ```
   [root@sym-01 11:32:55 /data/mysql/mysql3306/data/test]
    $ py_innodb_page_info -v t.ibd
    page offset 00000000, page type <File Space Header>
    page offset 00000001, page type <Insert Buffer Bitmap>
    page offset 00000002, page type <File Segment inode>
    page offset 00000003, page type <Tablespace SDI Index page>
    page offset 00000004, page type <B-tree Node>, page level <0001>
    page offset 00000005, page type <B-tree Node>, page level <0000>
    page offset 00000006, page type <B-tree Node>, page level <0000>
    page offset 00000007, page type <B-tree Node>, page level <0000>
    page offset 00000008, page type <B-tree Node>, page level <0000>
    page offset 00000009, page type <B-tree Node>, page level <0000>
    page offset 0000000a, page type <B-tree Node>, page level <0000>
    page offset 0000000b, page type <B-tree Node>, page level <0000>
    page offset 0000000c, page type <B-tree Node>, page level <0000>
    page offset 0000000d, page type <B-tree Node>, page level <0000>
    page offset 0000000e, page type <B-tree Node>, page level <0000>
    page offset 0000000f, page type <B-tree Node>, page level <0000>
    page offset 00000010, page type <B-tree Node>, page level <0000>
    page offset 00000011, page type <B-tree Node>, page level <0000>
    page offset 00000012, page type <B-tree Node>, page level <0000>
    page offset 00000013, page type <B-tree Node>, page level <0000>
    page offset 00000014, page type <B-tree Node>, page level <0000>
    page offset 00000000, page type <Freshly Allocated Page>
    Total number of page: 22:
    Insert Buffer Bitmap: 1
    Freshly Allocated Page: 1
    File Segment inode: 1
    B-tree Node: 17
    Tablespace SDI Index page: 1
    File Space Header: 1
