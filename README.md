# Tech-ur-onam
kalam is a vibrant and intricate floral art form traditionally created during the Indian festival of Onam. This project aims to bring the beauty of Pookalam to the digital world by generating stunning Pookalam designs using the power of Python programming.
cx=circle(r=147,fill="white")
c0=circle(r=145,fill="green")
c1 = circle(r=140,fill="black")
c2=circle(r=135,fill="violet")

r1=rectangle(w=200,h=190,fill="maroon",stroke="safron")|repeat(15,rotate(50))
r2=rectangle(w=190,h=180,fill="brown",stroke="brown")|rotate(15)|repeat(15,rotate(50))
r3=rectangle(w=180,h=170,fill="red",stroke="red")|rotate(0)|repeat(15,rotate(50))
r4=rectangle(w=170,h=160,fill="silver",stroke="orange")|rotate(15)|repeat(15,rotate(50))
r5=rectangle(w=160,h=150,fill="yellow",stroke="yellow")|rotate(0)|repeat(15,rotate(50))
r6=rectangle(w=150,h=140,fill="white",stroke="white")|rotate(15)|repeat(15,rotate(50))

s1=circle(r=100,fill="black",stroke="none")
s2=circle(r=95,fill="#045504",stroke="none")
s3=circle(r=90,fill="#057405",stroke="none")
s4=circle(r=85,fill="#pink",stroke="none")
s5=circle(r=80,fill="#53e453",stroke="none")

p1=rectangle(w=130,h=130,fill="red",stroke="none")|rotate(15)|repeat(30,rotate(50))
p2=rectangle(w=120,h=120,fill="#e63e5b",stroke="none")|rotate(0)|repeat(10,rotate(50))
p3=rectangle(w=110,h=110,fill="green",stroke="none")|rotate(15)|repeat(10,rotate(50))
p4=rectangle(w=100,h=100,fill="#e63e5b",stroke="none")|rotate(0)|repeat(10,rotate(50))
p5=rectangle(w=90,h=90,fill="#f5778d",stroke="none")|rotate(15)|repeat(10,rotate(50))

a1=circle(r=50,fill="orange")
a0=ellipse(w=20,h=100,fill="orange",stroke="#d49117")|repeat(100,rotate(10))
ax=ellipse(w=20,h=110,fill="yellow",stroke="#fcfc67")|repeat(100,rotate(20))
a2=ellipse(w=20,h=90,fill="orange",stroke="#d49117")|repeat(100,rotate(20))
a3=ellipse(w=20,h=80,fill="yellow",stroke="#fcfc67")|repeat(100,rotate(20))

q1=ellipse(w=10,h=90,fill="tangerine")|repeat(200,rotate(5))
q2=ellipse(w=10,h=80,fill="gold",stroke="none")|repeat(20,rotate(10))
q3=ellipse(w=10,h=70,fill="maroon",stroke="yellow")|repeat(20,rotate(10))
d1=rectangle(w=50,h=50,fill="orange",stroke="none")|repeat(100,rotate(15))
d2=rectangle(w=40,h=40,fill="tan",stroke="blue")|repeat(100,rotate(15))
d3=rectangle(w=30,h=30,fill="brown",stroke="none")|repeat(100,rotate(15))
q4=circle(r=15,fill="purple")
q5=circle(r=10,fill="pearl")
q6=circle(r=5,fill="white")

show(cx,c0,c1,c2,r1,r2,r3,r4,r5,r6,s1,s2,s3,s4,p1,p2,p3,p4,p5,a1,a0,ax,a2,a3,q1,q2,q3,d1,d2,d3,q4,q5,q6)
