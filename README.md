# Quiz-Management
a=['a']
b=['c']
c=['b']
d=['d']
a1=['d']
b1=['b']
c1=['c']
d1=['a']
e=['a']
f=['d']
def opt(a,b,c,d):
	print('')
	print('A : ',a,end='	')
	print('B : ',b)
	print('C : ',c,end='	')
	print('D : ',d,'\n')
score=0
print('1) How Much color does National Flag have ?')
opt(3,1,4,2)
n=input('enter the choice : '.title()).lower()
if n in a:
	score+=1
print('Correct answer is : 3'.title())
print('Score : ',score,'\n')
print('2) What is the National Friut of India ?')
opt('apple','banana','mango','orange')
n=input('enter the choice : '.title()).lower()
if n in b:
	score+=1
print('Correct answer is : mango'.title())
print('Score : ',score,'\n')
print('3) What is the National sport game of India ?')
opt('Cricket','Hockey','Kabaddi','Chess')
n=input('enter the choice : '.title()).lower()
if n in c:
	score+=1
print('Correct answer is : Hockey'.title())
print('Score : ',score,'\n')
print('4) Who is Present President of India ?')
opt('Modi','Stalin','Abdulkalam','RamnathGovind')
n=input('enter the choice : '.title()).lower()
if n in d:
	score+=1
print('Correct answer is : RamnathGovind'.title())
print('Score : ',score,'\n')
print('5) Who is the God of Cricket ?')
opt('ViratKohli','Ganguly','Dravid','SachinTendulkar')
n=input('enter the choice : '.title()).lower()
if n in a1:
	score+=1
print('Correct answer is : SachinTendulkar'.title())
print('Score : ',score,'\n')
print('6) How Much Oscar does AR Rahman won ?')
opt(3,2,0,1)
n=input('enter the choice : '.title()).lower()
if n in b1:
	score+=1
print('Correct answer is : 2'.title())
print('Score : ',score,'\n')
print('7) How much official language does India has ?')
opt(10,5,22,25)
n=input('enter the choice : '.title()).lower()
if n in c1:
	score+=1
print('Correct answer is : 22'.title())
print('Score : ',score,'\n')
print('8) Who is the current president of USA ?')
opt('JoeBiden','DonaldTrump','modi','BarackObama')
n=input('enter the choice : '.title()).lower()
if n in d1:
	score+=1
print('Correct answer is : JoeBiden'.title())
print('Score : ',score,'\n')
print('9) What is the Capital of England ?')
opt('Londan','NewYork','Washington','Denver')
n=input('enter the choice : '.title()).lower()
if n in e:
	score+=1
print('Correct answer is : Londan'.title())
print('Score : ',score,'\n')
print('10) What was Chennai originally Called ?')
opt('ElectricCity','Chennai','Patnam','Madras')
n=input('enter the choice : '.title()).lower()
if n in f:
	score+=1
print('Correct answer is : 3'.title())
print('Score : ',score,'\n')
print('Your score : '.title(),score)
