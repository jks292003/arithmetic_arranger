def arithmetic_arranger(list1,condition):
  if condition=="True":
    if len(list1)<5:
      line1=""
      line2=""
      line3=""
      line4=""
      side_space="    "
      for i in list1:
        list2=[ ]
        list2=i.split(" ")
        space = max(len(list2[0]), len(list2[2]))
        if list2[1]=="+" or list2[1]=="-":
         if list2[0].isnumeric() and list2[2].isnumeric():
            if len(list2[0])<5 and len(list2[2])<5:
              num1=int(list2[0])
              num2=int(list2[2])
              if list2[1]=="+":
                sum=num1+num2
                line4 += "    " + str(sum).rjust(space + 2)
              else:
                sum=num1-num2
                line4 += "    " + str(sum).rjust(space + 2)
              line1 += list2[0].rjust(space + 6)
              line2 += list2[1].rjust(5) + ' ' + list2[2].rjust(space)
              line3 += side_space + '-' * (space + 2)
            else:
              return "Error: Numbers cannot be more than four digits."
              
         else:
             return"Error: Numbers must only contain digits."
             
        else:
                return "Error: Operator must be '+' or '-'."
                
    else:
       return"Error: Too many problems."
    return line1 + '\n' + line2 + '\n' + line3 + '\n' + line4
  else:
    return "not true"
    
