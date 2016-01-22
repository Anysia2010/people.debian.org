#!/bin/bash
make
ssh people.debian.org "rm -rf ~/public_html/*"
ssh people.debian.org "ln -s ~/debian ~/public_html/debian"
scp -rp * people.debian.org:public_html/
