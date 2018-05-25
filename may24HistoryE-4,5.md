    1  sudo apt-get install jq -y
    2  mkdir m2e4
    3  cd m2e4
    4  pwd
    5  touch canadiana.sh
    6  nano canadiana.sh
    7  chmod 755 canadiana.sh
    8  ./canadiana.sh
    9  history
   10  history < may24exer4.md
   11  history > may24E4.md
  
  Adding all of the work from today.

   12  cd
   13  cd faillog
   14  nano may24E4.md
   15  cd
   16  pip install https://github.com/DocNow/twarc/archive/v1.2.0.tar.gz
   17  twarc configure
   18  twarc search hist3814o > search.json
   19  sudo npm install json2csv --save -g
   20  json2csv -i search.json -o out.csv
   21  % utils/sort_by_id.py tweets.jsonl > sorted.jsonl
   22  twarc dehydrate tweets.jsonl > tweet-ids.txt
   23  twarc dehydrate search.jsonl > tweet-ids.txt
   24  twarc dehydrate search.json > tweet-ids.txt
   25  nano tweet-ids.txt
   26  history
   
