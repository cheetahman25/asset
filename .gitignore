#!/bin/bash
DOM=$1
assetfinder --subs-only $DOM | httpx -nc -title --content-length -status-code -silent >> $DOM.txt
