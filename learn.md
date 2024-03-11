1. 垃圾桶操作:
   ```s
   1. 删除文件至垃圾桶(不是利用rm这种不可逆删除)
   trash-put filename
   trash-put directory
   2. 查看垃圾桶文件 
   trash-list
   3. 删除垃圾桶文件(此时就是彻底删除了)
   trash-rm filename
   trash-rm directory
   4. 从垃圾桶恢复
   trash-restore filename
   trash-restore directory
   ```