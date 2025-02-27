DISCLAIMER
==========
Please note: all tools/ scripts in this repo are released for use "AS IS" without any warranties of any kind, including, but not limited to their installation, use, or performance. We disclaim any and all warranties, either express or implied, including but not limited to any warranty of noninfringement, merchantability, and/ or fitness for a particular purpose. We do not warrant that the technology will meet your requirements, that the operation thereof will be uninterrupted or error-free, or that any errors will be corrected.
Any use of these scripts and tools is at your own risk. There is no guarantee that they have been through thorough testing in a comparable environment and we are not responsible for any damage or data loss incurred with their use.
You are responsible for reviewing and testing any scripts you run thoroughly before use in any non-testing environment.

See [the wiki](https://github.com/10gen-labs/sleepy.mongoose/wiki) for documentation.

### Remark

Compatible with mongoDB 4.x version.

Before start it, run script below in bash/CMD(don't use Powershell)

```
conda create -n py2.7 python=2.7
conda activate py2.7
pip install pymongo==1.9
```

And add `self.send_header('Access-Control-Allow-Origin', '*')` to MongoHTTPRequest.call_handler in httpd.py (already done in this repo).
