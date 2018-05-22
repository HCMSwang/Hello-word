# hello-word
#1.打印功提示
  print("="*50)
  print("  名字关系系统 V8.6")
  print(" 1:增加一个新的名字")
  print(" 2:删除一个名字")
  print(" 3:修改一个名字")
  print(" 4:查询一个名字")
  print(" 5:退出系统")
  print("="*50)

  names = [] #定义一个空的列表用来存储添加的名字
  while 2>1:
     #2.获取用户的选择
      num = int(input("请输入功能序号:"))
     #3. 根据用户的选择，执行相应的功能
      if num==1:
          numAdd = input("请输入名字:")
         names.append(numAdd)
         print(names)
     elif num==2:
        del_num = input("请输入您要删除的名字:")
         names.remove(del_num)
         print(names)
 
