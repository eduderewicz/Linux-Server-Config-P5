# Linux-Server-Config-P5
Deployment of Sports Catalog (P3: )

IP address:
52.34.60.21

SSH port:
2200

URL:
http://ec2-52-34-60-21.us-west-2.compute.amazonaws.com/

Summary of software installed and config changes:
- Apache2 server
- postgres
- Python libraries (flask, sqlaclhemy, psycopg2, )
- Disabled root ssh
- modified SSH, firewall, http, ntp ports
- configured uncomplicated firewall (UFW)
- Configured a virtual environment running python flask implementation
- ported project 3 to AWS instance including migration from SQLite DB to PostgreSQL DB

3rd party Resources used:
- Python docs
- PostgreSQL docs
- http://stackoverflow.com/questions/5377960/whats-the-best-practice-to-git-clone-into-an-existing-folder
- http://askubuntu.com/questions/86822/how-can-i-copy-the-contents-of-a-folder-to-another-folder-in-a-different-directo
- Github Help Docs
- https://discussions.udacity.com/t/p5-how-i-got-through-it/15342/15
- https://discussions.udacity.com/t/project-5-resources/28343
- https://discussions.udacity.com/t/markedly-underwhelming-and-potentially-wrong-resource-list-for-p5/8587
