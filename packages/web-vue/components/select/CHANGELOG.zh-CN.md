```yaml
changelog: true
```

## 2.18.0

`2022-03-04`

### 💎 功能优化

- 选择框展示使用 flex 布局方式 ([#778](https://github.com/arco-design/arco-design-vue/pull/778))
- trigger-props 属性可以覆盖默认属性 ([#778](https://github.com/arco-design/arco-design-vue/pull/778))

### 🐛 问题修复

- 修复 label 属性失效的问题 ([#777](https://github.com/arco-design/arco-design-vue/pull/777))
- 修复 option 的属性没有同步更新的问题 ([#777](https://github.com/arco-design/arco-design-vue/pull/777))


## 2.18.0-beta.2

`2022-02-25`

### 🆕 新增功能

- 增加 `search-delay` 属性，并默认为 `500ms` ([#728](https://github.com/arco-design/arco-design-vue/pull/728))


## 2.18.0-beta.1

`2022-02-18`

### ⚠️ 重点注意

- 组件使用 context 重构，允许对 Option 组件的封装使用 ([#688](https://github.com/arco-design/arco-design-vue/pull/688))
- 增加 `valueKey` 属性，选项 value 支持 object 形式 ([#688](https://github.com/arco-design/arco-design-vue/pull/688))
- <option> 组件的类名由 arco-dropdown-option 改为 arco-select-option，并使用 flex 垂直居中布局 ([#688](https://github.com/arco-design/arco-design-vue/pull/688))


## 2.16.0

`2022-01-21`

### 🆕 新增功能

- 增加自定义图标插槽 ([#634](https://github.com/arco-design/arco-design-vue/pull/634))


## 2.15.0

`2022-01-14`

### 💎 功能优化

- 优化加载中状态显示 ([#557](https://github.com/arco-design/arco-design-vue/pull/557))


## 2.14.3

`2022-01-12`

### 🐛 问题修复

- 调用虚拟列表的 `scrollTo` 函数时缺失了参数 ([#543](https://github.com/arco-design/arco-design-vue/pull/543))


## 2.14.2

`2022-01-10`

### 🐛 问题修复

- 修复按需加载没有导入样式的问题 ([#536](https://github.com/arco-design/arco-design-vue/pull/536))


## 2.13.0

`2021-12-31`

### 🐛 问题修复

- 修复搜索时中文输入法问题 ([#481](https://github.com/arco-design/arco-design-vue/pull/481))
- 修复在 `drawer` 中 placeholder 显示不全的问题 ([#481](https://github.com/arco-design/arco-design-vue/pull/481))


## 2.11.1

`2021-12-20`

### 🐛 问题修复

- 修复使用 JSX 时，Group 不可用的问题 ([#427](https://github.com/arco-design/arco-design-vue/pull/427))


## 2.10.1

`2021-12-14`

### 🐛 问题修复

- 修复 options 属性中 disabled 失效的问题 ([#385](https://github.com/arco-design/arco-design-vue/pull/385))
- 修复 bordered 属性未生效的问题，添加示例 ([#385](https://github.com/arco-design/arco-design-vue/pull/385))


## 2.10.0

`2021-12-10`

### 💎 功能优化

- 输入框可编辑时，点击不会关闭下拉菜单 ([#348](https://github.com/arco-design/arco-design-vue/pull/348))

### 🆕 新增功能

- 增加 fallback-option 和 show-extra-options 属性 ([#347](https://github.com/arco-design/arco-design-vue/pull/347))

### 🐛 问题修复

- 修复组件在 JSX 使用中出现警告、插槽不能使用变量的问题 ([#347](https://github.com/arco-design/arco-design-vue/pull/347))
- 修复多选输入框首次点击图标不能弹出下拉菜单的问题 ([#347](https://github.com/arco-design/arco-design-vue/pull/347))


## 2.8.0

`2021-12-01`

### 🆕 新增功能

- 增加 `tagProps` 的支持 ([#307](https://github.com/arco-design/arco-design-vue/pull/307))


## 2.6.0

`2021-11-19`

### 🆕 新增功能

- 增加 `footer` 插槽 ([#201](https://github.com/arco-design/arco-design-vue/pull/201))
- 增加 `trigger-props` 属性 ([#197](https://github.com/arco-design/arco-design-vue/pull/197))

### 🐛 问题修复

- 修复 `option` 插槽没有传出 `data` 参数的问题 ([#200](https://github.com/arco-design/arco-design-vue/pull/200))


## 2.5.0

`2021-11-18`

### ⚠️ 重点注意

- 将 2.4.0 添加的 `options.label` 的自定义渲染移动到 `options.render` 上 ([#183](https://github.com/arco-design/arco-design-vue/pull/183))
- `<option>` 添加 label 属性支持 ([#183](https://github.com/arco-design/arco-design-vue/pull/183))


## 2.4.0

`2021-11-17`

### 🆕 新增功能

- 增加 `option` 插槽 ([#170](https://github.com/arco-design/arco-design-vue/pull/170))
- `options.label` 支持自定义渲染 ([#170](https://github.com/arco-design/arco-design-vue/pull/170))


## 2.1.0

`2021-11-05`

### 🐛 问题修复

- 修复 `#empty` 插槽丢失的问题 ([#96](https://github.com/arco-design/arco-design-vue/pull/96))


## 2.0.3

`2021-10-29`

### 🐛 问题修复

- 修复清除按钮在多选模式下不显示的问题 ([#38](https://github.com/arco-design/arco-design-vue/pull/38))

