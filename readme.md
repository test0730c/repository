git config --global user.name "Name"
git config --global user.email email@mail.ru
mkdir local_rep
cd local_rep
git init
git remote add origin  <ссылка на удаленный репозиторий>

на этом этапе изменяем, удаляем, добавляем файлы в влокальном репозитории

git add --all
git commit -m "comment"
git push -u origin master
