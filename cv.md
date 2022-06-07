# **Tatsiana Radkevich**

---

## **Contact**

**Phone:** +375-29-873-78-09
**E-mail** <TatsianaRadkevich1403@gmail.com>
**GitHub** [Tatsiana1403](https://github.com/Tatsiana1403)

---

## **About me**

## I am 31 years old, my first education is law. At the moment, there was a desire to change the field of activity and try to realize oneself in another profession. Received a second degree in web design. During the training, I got acquainted with the basic skills of html, css, js. There is a desire to continue education in this direction.

## **Skills**

- HTML
- CSS
- JavaScript (basic)
- PHP, MySQL (basic)
- Git/GitHub
- Photoshop, CorelDRAW, Adobe Animate

---

## **Code Examples**

(a program that converts from old Russian units of measurement to modern metric system)

```
let unit = +prompt ("Введите код единицы измерения: 1 – верста, 2 – сажень, 3 – аршин, 4 – вершок");
let vers1 = 0.0009374;
let saj2 = 0.4687;
let ar3 = 1.406;
let versh4 = 22.5;
let len;
if (unit!==1 && unit!==2 && unit!==3 && unit!==4) {
	alert ("Неверно введен код. Попробуйте еще раз (нажмите F5 или обновите страницу).");
}
else {
	do {
		len = +prompt ("Введите длину в выбранных единицах измерения ");
	}
	while (isNaN(len) || typeof len!=="number" || len<=0);
	switch (unit) {
		case 1: document.write (len + " вер. = " + len/vers1 + " м.");break;
		case 2: document.write (len + " саж. = " + len/saj2 + " м.");break;
		case 3: document.write (len + " ар. = " + len/ar3 + " м.");break;
		case 4: document.write (len + " верш. = " + len/versh4 + " м.");
	}
}
```

---

## **Education**

**Belarusian State University** - lawyer
**School of Business of Belarusian State University** - web-desing

---

## **Languages**

**Russian** - native
**Belarussian** - native
**English** - A1
