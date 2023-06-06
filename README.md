# GitHub_2

*На локальном репозитории сделать ветки для:*
- Postman						       
- Jmeter						       
- CheckLists						       
- Bag Reports								
- SQL
- Charles
- Mobile testing
1.
 *1.1. Создать на GitHub репозитрой, в котором будут располагаться ветки* 
 + `GitHub_2`
 
 *1.2. Клонируем внешний репозиторий на локальный репозиторий*

+ `git clone https://github.com/lilytsts/GitHub_2.git`

 1.3. Заходим в склонированный репозиторий 
 
 + `cd HW_31_group/`
 
 1.4. Создаем ветки Postman, Jmeter, CheckLists, Bag Reports, SQL, Charles, Mobile testing:

+ `git branch Postman`
+ `git branch Jmeter`
+ `git branch CheckLists`
+ `git branch Bag_Reports`
+ `git branch SQL`
+ `git branch Charles`
+ `git branch Mobile_testing`

      
*2. Запушить все ветки на внешний репозиторий*

+ `git push -u origin Postman`
+ `git push -u origin Jmeter`
+ `git push -u origin CheckLists`
+ `git push -u origin Bag_Reports`
+ `git push -u origin SQL`
+ `git push -u origin Charles`
+ `git push -u origin Mobile_testing`

*3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта*

+ `git checkout BagReports`
+ `cat >>  br.txt`
+ `ctrl+c`

      
*4. Запушить структуру багрепорта на внешний репозиторий*

+ `git add .`
+ `git commit -m "add new file"`
+ `git push`


*5. Вмержить ветку Bag Reports в Main*

+ `git checkout main`
+ `git merge BagReports`

      
*6. Запушить main на внешний репозиторий.*

+ `git push -u origin main`


*7. В ветке CheckLists набросать структуру чек листа*

+ `git checkout CheckLists`
+ `cat >> CheckLists.json`
+ `ctrl+c`

*8. Запушить структуру на внешний репозиторий*

+ `git add .`
+ `git commit -m "add new file"`
+ `git push`


*9. На внешнем репозитории сделать Pull Request ветки CheckLists в main*

+ `Переходим на внешний репозиторий в ветку CheckLists, нажимаем кнопку Compare&pull requset`

*10. Синхронизировать Внешнюю и Локальную ветки Main*

+ `git checkout main`
+ `git fetch`- просмотрим действительно ли были какие-то изменения на внешнем репозитории
+ `git pull`
