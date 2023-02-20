# Project 9

## Original Output Image

![Original Output Image](./ass9.1-before.png)

## Task 1: Achieve the following Output using JavaScript DOM Manipulation

![Task 1 Image](./ass9.1-after.png)

## JavaScript Code:

```js
document.querySelector(".caption .title").style.color = "#dc143c";
```

---

## Task 2: Achieve the following Output using JavaScript DOM Manipulation

![Task 2 Image](./ass9.2-after.png)

## JavaScript Code:

```js
const btn = document.querySelector(".add-to-cart");

btn.addEventListener("mouseover", () => {
  btn.style.background = "#dc143c";
});
btn.addEventListener("mouseleave", () => {
  btn.style.background = "#3c8067";
});
```
