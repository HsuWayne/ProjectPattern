# ProjectPattern
project pattern memo

project/
├ build 
├ node_modiles
│
├ public  //靜態資源
│  ├ electron 設定檔
│
├ src
│  ├ assets //資源（字體、圖片等）
│  ├ model  //API模組
│  │  ├ api  //API class base on pages
│  │  └ engine  //API axios runner
│  │
│  ├ storage //global state
│  │  ├ lib  //all kind of global state
│  │  └ index.ts //export global state
│  │
│  ├ style //style model
│  │  ├ abstracts  //antdVar, customize var base on Design System from UI/UX
│  │  ├ base  //base style (font, color, align, float...etc)
│  │  ├ component  //style for global component in new-utility
│  │  ├ view  //style for pages in view
│  │  └ main.less  //manage all ".less" files
│  │
│  ├ -utility //global components and functions
│  │  ├ hook  //customize hook
│  │  ├ component
│  │  └ functions... //helper/format/validation...
│  │
│  ├ view //pages
│  │  ├ files... //all category pages base on Design System from UI/UX
│  │  ├ DemoPage //only for demo, collect all global components
│  │  └ LayoutTemplate //Pages Router main and only Controller
│  │
│  └ index.tsx...
│
├ test // e2e test file
│
└ 其他設定檔...
