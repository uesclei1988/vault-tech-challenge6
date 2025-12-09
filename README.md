git clone https://github.com/seuuser/vault-tech-challenge.git
cd vault-tech-challenge

for i in {6}
do
  echo "commit $i" >> log.txt
  git add .
  git commit -m "Commit $i"
done

git push
# vault-tech-challenge6
