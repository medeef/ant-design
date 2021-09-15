---
order: 8
title:
  zh-CN: 卡片式页签
  en-US: Card type tab
  ru-RU: Карточки
---

## zh-CN

另一种样式的页签，不提供对应的垂直样式。

## en-US

Another type of Tabs, which doesn't support vertical mode.

```jsx
import { Tabs } from 'antd';

const { TabPane } = Tabs;

function callback(key) {
  console.log(key);
}

ReactDOM.render(
  <Tabs onChange={callback} type="card">
    <TabPane tab="Новости" key="1">
      Content of Tab Pane 1
    </TabPane>
    <TabPane tab="Медиагалерея" key="2">
      Content of Tab Pane 2
    </TabPane>
    <TabPane tab="Публикации" key="3">
      Content of Tab Pane 3
    </TabPane>
    <TabPane tab="Календарь событий" key="4">
      Content of Tab Pane 4
    </TabPane>
    <TabPane tab="Пресс-релизы" key="5">
      Content of Tab Pane 5
    </TabPane>
    <TabPane tab="Интервью" key="6">
      Content of Tab Pane 6
    </TabPane>
    <TabPane tab="Выступления" key="7">
      Content of Tab Pane 7
    </TabPane>
  </Tabs>,
  mountNode,
);
```
