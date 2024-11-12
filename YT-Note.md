# 1. npm init

# 2. readme.md

# 3. git init

# 4. git add .

# 5. git commit -m "add initial files for backend"

# 6. git branch -M main

# 7. git remote add origin https://github.com/itz-XD/YT-backend.git

# 8. git push -u origin main

# 9. create folder 📁: public > ✅✅✅✅✅

# 10. git status - you cant push this file kyuki `git status` dekhoge to usne kaha tha ki aapne `folder` banaye hai, mai to file's ko track karta hoon. folder ke ander folder wo abhi `empty` hai to usko push karna koi sence nahi banata git ke liye.. ye senario aapke sath bhi aayega kafi bar aayega. to isliye hum yaha git ka brush up karenge ki aur kya kya hum git ke ander sikh sakte hai sath hi sath me taki professionaly aap ish tarah ke kaam karo. to ish tarah ki jab files aati hai to sabse pahle hum kya karte hai wahape ek new file create kar dete hai aur jis tarah se hum `.gitignore` banate hai waise hi `.gitkeep` file banate hai ab kyuki ye file aagayi hai ish file ke ander hota kuch nahi hai ye file hoti empty hai but ish file se kya hai ish type ke folders banane hai temprory jo jaruri bhi hai hamare work flow ke liye aur jinko push bhi karna hai hume aur track bhi rakhna hai to kis tarah se rakhe `empty folder` to is liye hum waha pe empty file bana dete hai `.gitkeep` waise to ish file ka naam kuch bhi ho sakta tha but ye ek standard proceajor hai jo hum use karte hai.

## ab agar me yaha par dekhu `git status` to actully me wo file yaha pe bol raha hai ki thik hai public ke ye temprory wagera sab aapko mai yaha pe track karke rakhunga yaha pe.

---

# Thik hai ji ab itna kaam to ha gaya. ab obviously si baat hai yaha pe hume 2-3 file lagengi hi lagengi

## Sabse pahli file to hume lagegi wo hai `.gitignore` kyuki obvious si baat hai ab hume professionally kaam kar rahe hai. professionally jab kaam kar rahe ho to kafi `Api's` bhi use karoge kafi `key's` bhi use karoge kafi `secret's` bhi use karoge lakin wo sari cheje to git me push nahi karni hai aachi baat bhi nahi hoti hai to isliye hum yaha pe `.gitignore` ek file banaange kyuki jo jo files hume push nahi karni hai sensitive files hai un sabko hum yaha par rakh paye.

## Ek sabse intresting cheej hai ki aapke par ek `gitignore generator` bhi hai market me to ye kya karte hai jis tarah ka aapka project hai uspe base aapko projects files wagera sab generate karke de dete hai. open the website and search `node`. to ye dekhiye node ki jitni bhi files hai jo sab ideally honi chaiye thi `.gitignore` me to wo hoti hai to yaha pe usually jab bhi professional code likhte hai to copy karte hai aur `.gitignore` me lake past kar dete hai, ab aapki jitni bhi files hai jo nahi jani chaiye wo yaha pe hai but aapko agar lagta hai ki kuch aur bhi honi chaiye to aap add kar sakte hai jo jaise `node_modules/` ho gaya, `jspm_packages/` ho gaya, `web_modules/` ho gaya. ye usually git pe `recreate` ki ja sakti hai to nahi karte hum. environment variable bhi dekhiye `.env`, `.env.test`, `.env.production` jitne bhi environment variables hai wo sab yaha pe track ho rahe hai ab kyuki sab cheje track ho rahi hai aache se to obvious si baat hai ab aap `environment` variable file bhi banana chahoge to hum ek file banate hai `.env` ye file hoti hai `environment variable` file. jab bhi hum cheejo ko production me push karenge to ye environment variable system se uthaye jate hai taki ye secure rahe ye file se nahi uthaye jate to environment variable jaise hi aapke backend ka source code `productoin` pe jaayega, `Aws` pe jaye cahe `digital ocean` pe jaye waha pe bhi un services pe aapko environment variables ke fields milte hai to `key value` waha pe bhi add kar dete ho.✅✅✅✅✅

# To itna kaam to hamara ho gaya aur hume samajh bhi aagaya ki ek ek cheej hum kyu kar rahe hai kya kya iske liye jaruri hai aur kaise ye sara kaam hoga. thik hai itna kaam to ho gaya `package.json` bhi aagaya `readme` bhi aagaya lakin ab hamari `index` file kahan hai kyuki `package.json` me promise karke aaye the na ki hamari `main file` `index.js` hogi, to usko promise bhi hum nibhaange hum abhi lakin itni jaldi nahi hum thoda sa aur kaam karenge.

## Hum root ke ander hi, ek aur yaha pe folder📁 banaange iska naam hai `src` ab ye totally totally aap pe depend karta hai ki aap sara ka sara directory file yahi rakh lo ya `source` ke ander rakh lo, sirf ek folder structure hai mujhe lagta hai ki hum `source` ke ander hum thoda sa aur organised rahenge to ish hisab se hum `source` ke ander sara ka sara rakh lete hai jitna bhi hamare pas me `work` rahega ya jo bhi hamari `files` rahegi, ushi ke ander hum rakhange.✅✅✅✅✅

## Ab `src` ke ander jate hai to hume 2-3 files lagengi, sabse easy mujhe kya lagta hai in file ko create karne ke liye ki aap kar sakte hai `right click` karke wagera lakin kafi time aapka save ho jata hai agar aap `command line` se kare to. Agar aap `git bash` use kar rahe hai to aap bhi kya kar sakte hai touch file se alag alag files create kar sakte hai. `touch` 1. `app.js` jo mujhe lagegi hi lagegi 2. `constants.js` 3. `index.js`. ab touch command se ye files create karne ka fyda ye hai ki mai jaise hi enter krta hoon to `src` ke ander na ye sari ki sari files create ho gayi hai aur ye bahar chal jay ander chal jaye insab se mujhe koi problem nahi hai easily sara kaam ho jata hai. ek kaam to ye ho gaya hamara.✅✅✅✅✅

# Ab `src` ke ander mujhe kuch folders bhi banane hai jinke hum ek ek karke charcha karenge, ab ye kya hai ki wo folders me bana abhi nahi sakta kyuki wahi wali kahani har ek ke ander `.gitkeep` rakhna padega kyuki sabke ander files thodi na rakh sakta hoon to jaise jaise files aayegi wo sara kaam hota jayega lakin abhi ke liye hamare pas kafi kaam ho gaya hai to isko hum `git` pe `push` kar dete hai.✅✅✅✅✅ ki kis tarah se sara kaam hoga lakin abhi hamare `package.json` ko nahi pata hai ki aap kis tarah se kaam me loge kya sari cheeje hongi.. to hum kya karte hai ish package.json file pe bhi thoda sa work kar lete hai saripts wagera likh lete hai ki kis tarah se `aap` `open` karna hai `run` karna hai. to sabse pahle to mai kya karunga kyuki mujhe jo `syntax` use karna hai wo karna hai `import` wala `syntax` `require` wala `syntax` nahi. js ke ander 2 tarah se importing hoti hai 1. common.js se 2. module se. mai poore ke poore project me `module` rakhunga taki consistency bane rahe. iskliye mujhe kya karna hai kuch nahi yaha pe aake likhna hai `"type": "module",` to maine `package.json` me hi bata diya ki dekhiye ji apan ish tarah se chalne wale hai.✅✅✅✅✅

# thik hai ji itna kaam to ho gaya lakin ab mujhe ye bhi pata hai ki past me maine jab kuch padhai kari thi to mujhe pata hai ki jab bhi server ki file `reload` hoti hai ya kuchbhi aap changes perform karte ho to server `start` aur `stop` karna padta hai ab iske kai options hai aap isko kis tarah se karna chahte ho ya to har bar server `stop` kariye aur `start` kariye ye bhi thik hai. lakin itni files likhange itna aage jake code likhne wale hai to problem hogi to waise to `node js` ke ander `--watch` karke option aaya hai latest jaha se aap kaam kar sate hai lakin production grade me abhi itna nahi gaya hai wo, abhi bhi log ek utility use karte hai jiska naam hai `nodemon`

# To `nodemon` hum yaha pe introduce karenge, usko use karenge.. nodemoon hai kuch bhi nahi bas ye aapki file jaise hi `save` hoti hai `server` ko `restart` kar deta hai, bas itna hi kaam hai isse jayda iska koi bhi kaam nahi, aap nodemon par jaange to dekhange ki jydatar `dev dependencies` istemal hota hai, aacha `dependencies` aur `dev dependencies` me kya fark hai. `dev dependencies` wo dependencies hoti hai jo development ke dooran hum use karenge production me hum isko nahi leke jate hai hum usse koi file bhari halki hone se koi fark nahi padta kyuki ye sirf development me kaam aayega, jaise hi production me jayega to hum isko kaam me nahi lete hai. but aap yaha pe dekhange

```javascript
npm i nodemon ❌
```

# ish tarah se install karoge to `main dependencies` ban jaagi. to apko jydatar option milega ye ish tarah ka

```javascript
npm install --save-dev nodemon ❌
```

# yani ki `dev dependencies` development dependencies hai taki main production me iska koi antar na aaye, aur aap nodemon install kar ligiye. iske other option bhi aapko mil jaange

```javascript
npm i -D nodemon ✅✅✅✅✅
```

# ish tarah bhi aap `nodemon` ko install kar sakte hai kul mila ke baat hai ki aap `dev dependencies` install kar sakte hai. ab jaise hi mai install kar raha hoon to aap sabse pahle dekhange `node_modules` aaya lakin kyuki `.gitignore` me `node_modules` pahle se hi hai to `git` mera `track` nahi kar raha hai isko plus mare par ye `nodemon devDependencies` naam se alag se aaya hai `dependencies` to hai hi nahi abhi mare pas wo to hum aage jake baat karenge but `dev depencencies` hamare pas me aagayi hai `nodemon` ab nodemon kya hai ish `src` ke ander jo `index.js` file hai isme aap jo bhi likhoge insabko aake pas reload kar dega but batana padega na aise hawa me thodi karega to jaise hamare pas `test` command hoti hai script hoti hai `package.json` file ka ander mai `test` ko hata kar `dev` command yaha pe bana leta hoon aur `nodemon` se bolunga ki nodemon aap please ish file ko `reload` kar digiyega jab hi mai kuch kaam karu, to bada easy hai usko bol digiye ki isse kya run hoga `nodemon` ab nodemon ko karna kya hai `src` ke ander jana hai aur yaha pe `/index.js` naam ki file hai. bas jaise hi mai `npm run dev` to isko start kar digiye.

```javascript
"dev": "nodemon src/index.js" ✅✅✅✅✅
```

# 🍃🍃🍃 NODEMON SETUP END 🍃🍃🍃

# To ab hamare pas me `packages.json` file me bhi kuch changes aagaye hai aur humne ish files ko bhi modify kar diya hai, abhi thodi si aur cheejo ke baare me baat karenge specially ye jo `environment variables` hai na ye aur iska `module` jo hai inka thoda sa panga chalta hai to isko hum kaise resolve karte hai wo bhi dekhange, kyuki aap ek file ke ander cheej dekhange, agar aap `dotenv` search karenge environment variables ki to abhi bhi yaha pe thoda sa issue ye hai ki inko jab bhi aapko use karna hai to aap actually me ish tarah easily `ES6` import nahi kar sakte aapko require wala `syntax` use karna padta hai `require('dotenv').config()` to iska bhi solution hai wo bhi hum dekhange.

# Abhi ke liye hamare pas bhi bahut kaam ho gaya hai ki kis tarah se apna project wagera sab kuch set-up ho chuka hai aur uske baad bhi mai aapko aur ek kaam bataunga abhi han kaam kafi bataunga :)

## To abhi hum `git status` dekhte hai ek bar apna ki thik chal raha hai kya sab.. to thik hai kafi files wagera aa chuki hai aur obvious si baat hai in sabko track bhi ho chuka hai to sabko add bhi kar lete hai.. sabhi add kar dete hai aisuch koi dikkat nahi hai

```javascript
git add .
```

```javascript
git commit -m "setup project files - part 1"
```

## Aur kyuki humne `upstream` set kar diya hai to directly `git push` kar sakte hai

```javascript
git push ✅✅✅✅✅
```

## To `git push` karenge to hamare almost sare files waha pe chal jane chaiye

---

# Ab mujhe yaha pe na kuch folders 📁 bhi chaiye. `terminal` me `ls` command run karke dekhta hoon to `app, constants, index` ye sare file show honge. agar aap kisi folder ke ander se `cd ..` command run karke main source `src` pe aajaiye. ab `ls` command run karne se sare file show ho jaange. To ab mujhe `source` ke ander jake kuch folders 📁 create karne hai aur yahi folders 📁 aage jake mare kaam aange aur yahi hota hai actually me professional production grade project ka structure setup to usko bhi hum kar hi lete hai.

## To sabse pahle hum chalte hai hum src ke ander `cd src`, ab yaha pe abhi tk 3 files 🗒️ hai, mujhe kuch folders 📁 bhi chaiye to `mkdir` se mai folder 📁 bna sakta hoon.

### `1.` `controllers📁` - yaha pe meri hogi majorly functionality.

### `2.` `db📁` - yaha pe mai likhunga ki data base connect kaise karna hai, ab data base aapka `mongoodb` ho ya `postgrace` ho fark nahi padta, data base ka logic yaha likhta jata hai most of the time.

### `3.` `middlewares📁` - ab middlewares kya hote hai kuch nahi, koi bhi code ja aapko inbetween run krana hai. aapke pas ek req aayi wo req server fullfill kare usse pahle hi mai beach me kuch checking lagana chata hu to wo middlewares ke ander karta hoon. jaise ki suppose kariye ki aapke pas ek req aayi aur aap server se kuch information puch rahe ho but mai ek `middleware` laga dunga beach me ki aapki `cookies` mujhe jo taki mai pata karun pahle hi ki aap ush information ko lene `yoogya` ho ya nahi ho. to ye sara kaam hum `middlewares` ke ander karte hai.

### `4.` `models📁`

### `5.` `routes📁` - Abhi tk humne jo bhi project kiya uske ander humne `routes` kya kra `index` file ke ander hi likh diye, par kya hai professionally aisa nahi chalta hai kyuki `routes` bahut hi jyda complicated ho jate hai aur bahut sare hote hai to unka kaise ek standard approach rakhte hai to ek folder me hum alag se rakhange aur kafi detail me charcha karenge kis tarah se ye kaam kiya ja sakta hai.

### `6.` `utils📁` - Ab ye utils kya hai !! kuch nahi hai ji shortcut hai `utilities` ka, ab utils ke ander kya hai dekhaiye aap jab kaam karenge aapko bahut sari utilities lagengi. jaise ki `file uploading` utility hai. to file upload aap apne user hai profile me bhi karwaaoge videos me bhi karwaoge to kyu ka uski ek utility bna ke rakh di jaye, kai jagha aap `mailing` ka bhi use karoge to kyu na ek `mail` ki `utility` bna ke rakh di jaye aise aap aur bhi kaam karoge jaise ki joi tokens lena dena bahut sare aise kaam hote hai jo functionality bar bar repeat hogi to kyu na usko ek file folder 📁 me rakh diya jaye aur utilities bol diya jaye, jab hi kaam hoga waha se file le lange. to apni hi suwidha ke liye ye kaam kiya jata hai.

## To ye hamara ho gaya ek `professional structure project` ka, ab har company me ye structure thoda bahut alag hota hai 19-20 ka fark hota hai.

```javascript
mkdir controllers db middlewares models routes utils ✅✅✅✅✅
```

## Ab jaise hi mai ye enter karta hoon to mare sare ye project ban gaye hai, lakin problem abhi bhi wahi hai agar mai git se puchunga ki `git status` bata kya chal raha hai abhi to thik hai aapki package.json wagera to modify hue hai waise to nahi honi chaiye thi😅... hmmm `not staged`. stage nahi kra kya abhi kar dete hai `stage`. lakin aap dekhange ye jo controllers wagera hai in folders📁 ko abhi kuch bhi track nahi kar raha hai kyuki inke ander files🗒️ hi nahi hai ab ya to mai sabke ander jaaun aur ek ek ke ander `.gitkeep` rakhu, lakin koi sence bhi nahi hai unko rakhne ka kyuki un files 🗒️ me jaise kaise kaam aayega waise rakh dange tabka mare local me rahega.

# Sabse easy hai yaha pe jaiye `source contorll` me jo bhi aapko lagte hai ki karna chaiye change commit wo kar digiye. jitne bhi ye sab `packages` hai `public` `temprory` in sabko hum commit kar dete hai, `command line` se kariye ya `source contorll` se kariye kya hi fark padta hai

### Comment

`add structure changes` ❌❌❌❌❌

# Install `prettier` to be safe from future conflicts.

`npm i -D prettier` ✅✅✅✅✅

### Ab jaise hi aapne `prettier` install kra to kuch hua to hai hi nahi, prettier actually me jab hi aata hai to aapko actually me kuch thode se kaam karne padte hai 2-3 files 🗒️ aapko apni taraf se add karni padti hai.

`1.` `.prettierrc` - ye kya hoti hai ye sare ke sare prettier ke configurations hai

```javascript
{
    "sngleQuote": false,
    "bracketSpacing": true,
    "tabWidth": 2,
    "trailingComma": "es5",
    "semi": true ✅✅✅✅✅
}
```

## Ye to ho gaya ki mai apne poore project ka setup kis tarah se rakhunga, ab automatically yaha pe kya hoga prettier yaha pe ab jab aap left bottom me click karoge to prettier ko apne aap mil jayega ki aacha thik hai `prettier` hai aur kai bar project ko `restart` ya `reload` bhi karna padta hai.

`2.` `.prettierignore` - ab ye prettierignore kya karta hai ki kon kon se file me mujhe prettier ko impliment nahi karna hai wo mujhe bata do uske ander sabse important jo mai laga hu usually, meri jo `invironment` variable file hai na please usko touch mat karna kyuki usko syntak thoda sa na weard hota hai `key value pairs` to prettier jab jab kuch karne ki kosis karta hai hamesa kabada karta hai to mujhe pasand nahi hai, kisi bhi tarah ki .env mat lena.

```javascript
/.vscode
/node_modules
./dist

*.env
.env
.env.* ✅✅✅✅✅
```

# Ye hamara ho gaya basic ek configration ki kis tarah se `prettier` aur ye sab `setup` kiya jata hai.

# Abhi hamare par `prettier` ki settings ho gaye hai poori to hum isko stage kar dete hai aur prettier ka code push kar dete hai `add prettier config` commit push. ❌❌❌❌❌

<!-- EP FINISH 🏁🏁🏁 -->
