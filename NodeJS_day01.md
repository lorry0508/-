#  NodeJS day01

---
���׶�ͨ��NodeJS���˽��ˣ��Լ���������˽�javacscript��������



## ѧϰĿ��
1. ���������
   + ʲô��node.js�Լ�node.js���ص�
   + node.js�ʺ���ʲô
   + nodeJS����صĸ��ʲô��ģ�黯��ʲô��Common.jsģ�黯�淶
   + ģ�顢����npm�������ػ���
   + etc...
2. ������������
   + ����node.js�л���API��ʹ��
   + �ܹ�ʹ��npm�����
   + �ܹ�ʹ��ES6���﷨
   + �ܹ�ʹ��node.js����������web������
3. ������ʵս��
   + �ܹ�ʹ��Express��ܡ����mysql���ݿ��д��վ����
## 1.0 ��������
### 1.1 һЩ��̸

#### ���Ժͻ���

 - ����
    - ��д��������Թ淶������Ա��ѭ�ض����﷨�淶����д�����Ĵ��룬�ַ����ı����뱾�����߱�ִ�е�����
 - ������ƽ̨��
    - �ṩ��ִ�д���������������������Ҫ�����Լ������������֣��ͱ��������ض���ִ�л���

> ���磬ǰ�����е�Ч������������������У���˵Ĵ�������ڷ�����������



#### ǰ�˺ͺ��

| ������  | ����                                 |
| ---- | ---------------------------------- |
| ǰ��   | ҳ��ṹ������ҳ����ʽ����дҳ���ҵ���߼���ʹ��Ajax���ú�̨�ӿ� |
| ���   | �������ݿ⡢���Ⱪ¶�������ݿ��API�ӿ�              |
![�˴�����ͼƬ������][1]
![�˴�����ͼƬ������][2]


#### �������ս
##### 1 ���� 1994

������90������ң�������˾������liveScript��Ŀ��Ϊ��ʵ���û�����

##### 2 �������ս��һ�� 1995 - 1997

������˾NetscapeЯ��sun��˾�Ƴ���javascript����
΢���IE������Ƴ���JScript
ͬʱ��IE�����ͨ�������΢�����������ۣ�һ�ٻ�����������˾

__ŷ�޼����������Э�ᣨECMA����1998��6�£��ƶ���ECMAScript 2.0__

##### 3 �������ս������2004 - 2009

javascript��չ������ɫ����ҳ����ǵصġ�ţƤ޺��

���Ĳ�����������˾��ԡ�����������˻���������Firefox��

mozilla��˾������Դ�룬IE�����˵�7���汾����ʱҲð���˺ܶ����������

2008��12�£�Google Chrome����

__�ɹȸ跢��������������JS�������棨V8������__

![�˴�����ͼƬ������][3]

##### 4 ECMAScript 5.0  2009.12

__�ܽ᣺�������JS��ɣ�ECMAScript���� + DOM + BOM__



### 1.2 Node�Ĺ淶

Node.js ��һ������ Chrome V8 ����� JavaScript ���л����� 
Node.js ʹ����һ���¼�������������ʽ I/O ��ģ�ͣ�ʹ�������ָ�Ч��

#### �¼�����

```javascript
// DOM�е��¼�
$("#btn").on("click", function() {
  	// code
})

// Node�е��¼�
server.on("request", function() {
  	// code
})
```



#### ������ʽ I/O

```javascript
// js���ϵ���ִ�У����ǰ���δִ�У�������ִ�����������
// �����ǰִ�б�����Ŀִֹͣ��


// �¼�ע�ᡢ��ʱ����ajax�Ļص��������������¼��������Ŷ�ִ��
// ��ߴ���ִ�е�Ч��
// ������ʳ���Ŷ�
```

���¼�ѭ���ĸ����������ϸ����

#### npm

Nodejs�İ�����������ȫ�����Ŀ�Դ����̬ϵͳ

#### NodeJS��ɲ���

ECMAScript���� + __ȫ�ֳ�Ա__ + __����APIģ��__

> ע����Node.js�У�û��BOM��DOM��node���ṩ��������ݽ����ģ���������webҳ���

#### �������JS��Node��JS�Ĺ�ϵ

![](D:\�γ�\�γ�����\10_NodeJS\10_NodeJS(�ʼ�)\�ʼ�\images\nodejs-web.jpg)

### 1.3 �ܽ�

nodejs��ʲô��

nodejs���Ը�ʲô

 - ��phpһ����ʹ��javascript��д���Ϲ淶�ĺ��API�ӿڻ�����վ

 - ʹ��NodeJS����һЩʵ�õĹ��߻��߰�

 - **�ִ���ǰ�˿����м������е���Ŀ����Ҫ���롣�����ƽ̨99%����node�н���**

 - ����Socket����������������������֮��ļ�ʱͨѶ��Ŀ

 - ����Electron������https://electronjs.org���������������������vscode��

 - ect... 

 - [javascriptռ��]: https://madnight.github.io/githut/#/pushes/2019/1


  ![](D:\�γ�\�γ�����\10_NodeJS\10_NodeJS(�ʼ�)\�ʼ�\images\image_1b32gl0abfsp1ekp18a117dckf516.png)



---



## 2.0 ������װ

LTS�����Ƽ�����ҵ��ʹ�á��ǳ����ȶ���İ�װ���������ȶ�����ȫ

Current�����Ƽ�ѧϰ���߳���ȥʹ�á������µ���������Node��������



### 2.1 ��װNode����

 	˫����װ��Ӧ�汾�����ֱ��װ��C��

װ����֮��ͨ��cmd�������д��ڣ�ִ�а汾�ŵĲ�ѯ

![](D:\�γ�\�γ�����\10_NodeJS\10_NodeJS(�ʼ�)\�ʼ�\images\cmd.jpg)


### 2.2 ��������

�����ʶ��node�������ȥ�鿴�����������Ƿ����node·��

һ���������ϵͳ�Ļ��������������ǲ����û��Ļ�������

![](D:\�γ�\�γ�����\10_NodeJS\10_NodeJS(�ʼ�)\�ʼ�\images\path.jpg)

### 2.3 ִ��js�ķ�ʽ

| cmdС����     | ����            |
| ---------- | ------------- |
| ʹ���ϼ�ͷ      | ���ٶ�λ����һ��ִ�е����� |
| ʹ��tab��     | �Զ���ȫ·��        |
| ����cls      | ��������          |
| ������ Ctrl+C | �˳�REPL����      |
| ����ls      | �鿴��ǰĿ¼�ļ�          |
| ����cd      | ����ָ��Ŀ¼          |



> ##### ��REPL�����п���ִ��һЩjs�����





---



## 3.0 ES6�﷨

2015��6��17�� ECMAScript 6������ʽ�汾��Ҳ����ECMAScript 2015���˺�ÿ�����һ��

ES6���﷨�ڴ󲿷ֵ�������ж��ǿ���ʹ�ã��������в������������ʶ���ˣ������ʹ�ñ���Ҫͨ��������ǰת���ES5

### 3.1 ���������ķ�ʽ

�������������ʱ��ͨ��ʹ��var�ؼ������������ںܶ��ȱ��

1�����ڱ�����������������js����Ŀ��Ķ���

2�� û�п鼶������������ɱ�����Ⱦ



#### ʹ��let��������

- �����ڱ�����������������Ҫ����֮�����ʹ�ã����򱨴�

- �п鼶������{ }���Ǵ����
- �����ظ�����

```javascript
// ʹ��let�ؼ��ֶ������
console.log(c) // error: c is not defined
let c = 11
c += 1
```

```javascript
for(let i = 0; i < 10; i++) {
  // code
}
console.log(i) // error: i is not defined
```



#### ʹ��const��������

- ͬlet

- const����ĳ��������ܱ����¸�ֵ

- �����峣����ʱ�򣬱���ͬʱ��ֵ����Ȼ����


```javascript
// ʹ��const�ؼ��ֶ������
console.log(d) // error: d is not defined
const d = 11
```

```javascript
const d = 10
// ע�⣺const����ĳ����޷������¸�ֵ
d = 20 // typeError: Assignment to constant variable.
```

```javascript
// ע�⣺const����ĳ���,�����ڶ����ʱ���һ����ʼ����ֵ
const d
// SyntaxError: Missing initializer in const declaration
```

```javascript
for(let i = 0; i < 10; i++) {
  const a = "hello"
  console.log(a) // ���10�� hello
}
// { }�������򣬲�ͬ��{ }�в�ͬ��������
// �����������

// ---------------------------------

const a = "hello"
const a = "hello"
// SyntaxError: Identifier 'a' has already been declared
```



#### �⹹��ֵ

```javascript
let user = {
  	name: "zs",
  	age: 20,
  	gender: "��"
}

/*let name = user.name
let age = user.age
console.log(name)
console.log(age)*/

// ���ǽ⹹��ֵ�﷨ (ð�Ŵ���������)
let { name: username, age } = user
username = "ls"
console.log(username) // ls
console.log(age)  // 20

// ���let��Ϊconst����ô�����¸�ֵ��ʱ��ᱨ��
```



### 3.2 ��ͷ����

- ��ͷ����û���Լ���this��thisָ��**����**��ͷ����ʱ������**�ⲿִ�л���**��this
- ��ʱ����call/apply/bindҲ�޷��ı��ͷ������this
- ��ͷ��������û������
- ��ͷ��������new��**�ᱨ��**
- ��ͷ����û��arguments���ڼ�ͷ�����ڷ�������������ʵ���**�ⲿִ�л���**��arguments
- ��ͷ����û��prototype

```javascript
// ��ͨ����
function show(arg1, arg2) {
  	// code
}

// ��ͷ���� - �����������������ļ�д
/* (�β��б�) => {
  // code
} */
```



#### thisָ��

```javascript
btn.onclick = function() {
  	setTimeout(function() {
      	console.log(this) // Window
        this.style.backgroundColor = "red" // ����
  	}, 1000)
}
```

ʹ�ü�ͷ������

```javascript
btn.onclick = function() {
  	setTimeout(() => {
      	console.log(this) // <button id="btn">���<button>
        this.style.backgroundColor = "red" 
  	}, 1000)
}
```



> ### ��ͷ�����ڲ���this��Զָ���ͷ���������this



#### ��ͷ����-����

```javascript
/*function add(x, y) {
  	return x + y
}

// ��������
(x, y) => {
  	return x + y
}*/

var add = (x, y) => {
  	return x + y
}
console.log(add(1, 2)) // 3
```

����1

```javascript
// ��������β�ֻ��һ���������ſ���ʡ��
var add = x => {
  	return x + 10
}
console.log(add(1)) // 11
```

����2

```javascript
// ����Ҳ�ֻ��һ�д��룬�����ʡ�Ի����ź�return
var add = (x, y) => x + y
console.log(add(1, 2)) // 3
```

����3

```javascript
// �������������������֣��򶼿���ʡ��
var add = x => x + 20
console.log(add(3)) // 23
```



### 3.3 �����ж������Ժͷ���

ʹ�ÿ�ݷ�ʽ�������Ժͷ���

```javascript
let name = "zs"
let age = 22
function show() {
  	console.log('����zs')
}

/* let person = {
  	name: name,
  	age: age,
  	show: show
}
console.log(person) // {name: 'zs', age: 22, show: [Function: show]} */

let person = {
  name,
  age,
  show,
  say() {
    	console.log("ok")
  }
}
console.log(person)
// { name: 'zs', age: 22, show: [Function: show], say: [Function: say]} */



```


[1]: http://static.zybuluo.com/qiankunfaith/h9azwwsm2zbahr6c7sqok7k0/image_1b2sl8d6n1ulk152t1qlp1ebq40p.png
[2]: http://www.aseoe.com/uploadfile/2016/0831/20160831103230828.jpeg
[3]: http://static.zybuluo.com/qiankunfaith/nyh6e6qivt0e03itdh2544ko/image_1b32geknc1cg517d9lpjfgn16v39.png