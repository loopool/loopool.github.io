### 沁园春·雪

北国风光，千里冰封，万里雪飘。望长城内外，惟余莽莽；大河上下，顿失滔滔。山舞银蛇，原驰蜡象，欲与天公试比高。须晴日，看红装素裹，分外妖娆。

江山如此多娇，引无数英雄竞折腰。惜秦皇汉武，略输文采；唐宗宋祖，稍逊风骚。一代天骄，成吉思汗，只识弯弓射大雕。俱往矣，数风流人物，还看今朝。

### 编程字体

0Oo1Il The quick fox jumps over a lazy dog.。，

南去經三國，東來過五湖。南去经三国，东来过五湖。

### 代码测试

```javascript
function pow(x, n) {
  if (n == 1) {
    return x;
  } else {
    return x * pow(x, n - 1);
  }
}

alert( pow(2, 3) ); // 8
```
### English

> The remote names differ across my repositories, so I can't put the alias with an `origin` remote into my gitconfig?

If you want the same alias to work across all repos, you will have to set up consistent branch names.

Let's assume `origin` always points to your personal github repo, but for some repos your default branch lives in you repo while in other cases, your repo is a fork and your default branch lives in the `upstream` remote. In that case I suggest to add an `upstream` remote to all repos (even if it will be identical to `origin` when your repo contains the default branch). This allows you to use `upstream` in the alias and have your alias work across all repos again.