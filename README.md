# Stoooges
#step 1:
##使用os模块，把学员名字放在文件名上，最后放到一个文件夹内
###os.listdir(path)
###os.path.isdir(path_or_file)
###os.path.isfile(path_or_file)
###os.rename(old_filename, new_filename)

#step 2:
##把整个文件夹上传到Google Drive

#step 3:
##使用google drive内的**get direct link**应用得到文件名和download__link

#step 4:
##从文件名中得到stu_name, school
##从dowload_link中得到file_id
##(file_id可以生成view_link)

##保存于index_10.txt


#step 5:
##把上文提到的
###stu_name
###school
###file_id
###[view_link]('https://drive.google.com/file/d/{}/view?usp=sharing'.format(file_id))
###[download_link]('https://docs.google.com/uc?export=download&id={}'.format(file_id))
##填入表格

##在**Sublime Text**中打开，使用正则表达式替换文件名(例如'_'替换为'\t')，粘贴到excel表格中

#dependency: essays
