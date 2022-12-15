# de
de
import re
pattern = re.compile(ur'0?(13|14|15|17|18|19)[0-9]{9}')
str = u''
print(pattern.search(str))
