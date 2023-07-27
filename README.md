# ProjectPattern
### project pattern memo

project/<br>
├ build <br>
├ node_modiles<br>
│<br>
├ public  //靜態資源<br>
│  ├ electron 設定檔<br>
│<br>
├ src<br>
│  ├ assets //資源（字體、圖片等）<br>
│  ├ model  //API模組<br>
│  │  ├ api  //API class base on pages<br>
│  │  └ engine  //API axios runner<br>
│  │<br>
│  ├ storage //global state<br>
│  │  ├ lib  //all kind of global state<br>
│  │  └ index.ts //export global state<br>
│  │<br>
│  ├ style //style model<br>
│  │  ├ abstracts  //antdVar, customize var base on Design System from UI/UX<br>
│  │  ├ base  //base style (font, color, align, float...etc)<br>
│  │  ├ component  //style for global component in new-utility<br>
│  │  ├ view  //style for pages in view<br>
│  │  └ main.less  //manage all ".less" files<br>
│  │<br>
│  ├ -utility //global components and functions<br>
│  │  ├ hook  //customize hook<br>
│  │  ├ component<br>
│  │  └ functions... //helper/format/validation...<br>
│  │<br>
│  ├ view //pages<br>
│  │  ├ files... //all category pages base on Design System from UI/UX<br>
│  │  ├ DemoPage //only for demo, collect all global components<br>
│  │  └ LayoutTemplate //Pages Router main and only Controller<br>
│  │<br>
│  └ index.tsx...<br>
│<br>
├ test // e2e test file<br>
│<br>
└ 其他設定檔...<br>
