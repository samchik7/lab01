# lab01
export GITHUB_USERNAME=samchik7          
export GIST_TOKEN=token
alias edit=nano
mkdir -p ${GITHUB_USERNAME}/workspace




mkdir -p ${GITHUB_USERNAME}/workspace
cd ${GITHUB_USERNAME}/workspace
pwd
/Users/sam/samchik7/workspace
cd ..
pwd
/Users/sam/samchik7




$ mkdir -p workspace/tasks/
$ mkdir -p workspace/projects/
$ mkdir -p workspace/reports/
$ cd workspace




wget https://nodejs.org/dist/v6.11.5/node-v6.11.5-linux-x64.tar.xz
--2025-03-10 13:35:39--  https://nodejs.org/dist/v6.11.5/node-v6.11.5-linux-x64.tar.xz
Распознаётся nodejs.org (nodejs.org)… 104.20.22.46, 104.20.23.46
Подключение к nodejs.org (nodejs.org)|104.20.22.46|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 200 OK
Длина: 9356460 (8,9M) [application/x-xz]
Сохранение в: «node-v6.11.5-linux-x64.tar.xz»

node-v6.11.5-linu 100%[============>]   8,92M  62,7KB/s    за 2m 8s   

2025-03-10 13:37:47 (71,5 KB/s) - «node-v6.11.5-linux-x64.tar.xz» сохранён [9356460/9356460]
tar -xf node-v6.11.5-linux-x64.tar.xz
rm -rf node-v6.11.5-linux-x64.tar.xz
mv node-v6.11.5-linux-x64 node



ls node/bin
node	npm
echo ${PATH}
/Users/sam/.brew/bin:/usr/local/bin:/opt/homebrew/bin:/opt/homebrew/sbin:/Library/Frameworks/Python.framework/Versions/3.12/bin:/usr/local/bin:/System/Cryptexes/App/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/local/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/appleinternal/bin:/Library/Apple/usr/bin:/usr/local/share/dotnet:~/.dotnet/tools
export PATH=${PATH}:`pwd`/node/bin
echo ${PATH}
/Users/sam/.brew/bin:/usr/local/bin:/opt/homebrew/bin:/opt/homebrew/sbin:/Library/Frameworks/Python.framework/Versions/3.12/bin:/usr/local/bin:/System/Cryptexes/App/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/local/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/appleinternal/bin:/Library/Apple/usr/bin:/usr/local/share/dotnet:~/.dotnet/tools:/Users/sam/samchik7/workspace/node/bin
cat > scripts/activate<<EOF
export PATH=\${PATH}:`pwd`/node/bin
EOF
source scripts/activate
sudo gem install gist





(umask 0077 && echo ${GIST_TOKEN} > ~/.gist)

