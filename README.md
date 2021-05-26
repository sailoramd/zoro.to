{
  "moduleInfo": {
    "moduleName": "Zoro",
    "moduleInitials": "",
    "moduleDesc": "This is a module to get data from Zoro.to website enjoy.",
    "developer": "sailoramd",
    "moduleID": "73474883994874",
    "moduleImage": "https://pm1.narvii.com/6291/55276042f937ffe65cd921d5671aa3a0daa30ed5_hq.jpg
    "moduleVersion": 1,
    "moduleLenguage": "ENG",
    "moduleType": "Video",
    "baseURL": "https://zoro.to/",
    "moduleDeveloperSite": "https://mprotmod.github.io/Modules-KETSU/index.html",
    "UpdateSite": "https://raw.githubusercontent.com/sailoramd/zoro.to/main/README.md",
    "preferedServer": "Vidcloud",
    "preferedDownloadServer": "Vidcloud",
    "blackListed": [
      ""
    ]
  },
  "global": {
    "variables": [
      {
        "key": "",
        "value": ""
      }
    ],
    "cookies": [
      {
        "key": "",
        "value": ""
      }
    ],
    "headers": [
      {
        "key": "",
        "value": ""
      }
    ]
  },
  "mainPage": [
    {
      "request": {
        "url": "https://zoro.to/home",
        "method": "get",
        "headers": [
          {
            "key": "",
            "value": ""
          }
        ],
        "httpBody": null
      },
      "extra": {
        "commands": [
          {
            "commandName": "",
            "params": [
              {
                "key": "",
                "value": ""
              }
            ]
          }
        ],
        "extraInfo": [
          {
            "key": "",
            "value": ""
          }
        ]
      },
      "javascriptConfig": {
        "removeJavascript": true,
        "loadInWebView": false,
        "javaScript": "const DefaultLayouts = { ultraWideFull : 'ultraWideFull', ultraWide : 'ultraWide', wideFull : 'wideFull', wide : 'wide', wideStrechedFull : 'wideStrechedFull', wideStrechedFullDouble : 'WideStrechedFullDouble', wideStreched : 'wideStreched', wideStrechedDouble : 'wideStrechedDouble', wideStrechedFullList : 'wideStrechedFullList', wideStrechedList : 'wideStrechedList', doublets : 'doublets', doubletsDouble : 'doubletsDouble', doubletsFull : 'doubletsFull', doubletsFullDouble : 'doubletsFullDouble', doubletsConstant : 'doubletsConstant', doubletsDoubleConstant : 'doubletsDoubleConstant', doubletsFullConstant : 'doubletsFullConstant', doubletsFullDoubleConstant : 'doubletsFullDoubleConstant', longDoublets : 'longDoublets', longDoubletsDouble : 'longDoubletsDouble', longDoubletsFull : 'longDoubletsFull', longDoubletsFullDouble : 'longDoubletsFullDouble', longDoubletsConstant : 'longDoubletsConstant', longDoubletsDoubleConstant : 'longDoubletsDoubleConstant', longDoubletsFullConstant : 'longDoubletsFullConstant', longDoubletsFullDoubleConstant : 'longDoubletsFullDoubleConstant', triplets : 'triplets', tripletsDouble : 'tripletsDouble', tripletsFull : 'tripletsFull', tripletsFullDouble : 'tripletsFullDouble', tripletsConstant : 'tripletsConstant', tripletsDoubleConstant : 'tripletsDoubleConstant', tripletsFullConstant : 'tripletsFullConstant', tripletsFullDoubleConstant : 'tripletsFullDoubleConstant', longTriplets : 'longTriplets', longTripletsDouble : 'longTripletsDouble', longTripletsFull : 'longTripletsFull', longTripletsFullDouble : 'longTripletsFullDouble', longTripletsConstant : 'longTripletsConstant', longTripletsDoubleConstant : 'longTripletsDoubleConstant', longTripletsFullConstant : 'longTripletsFullConstant', longTripletsFullDoubleConstant : 'longTripletsFullDoubleConstant', none: ''};const CellDesings = { Special1 : 'Special1',Special2 : 'Special2',Special3 : 'Special3', small1 : 'small1', small2 : 'small2', normal1 : 'normal1', normal2 : 'normal2', normal3 : 'normal3', normal4 : 'normal4', normal5 : 'normal5', normal6 : 'normal6', normal7 : 'normal7', wide1 : 'wide1', wide2 : 'wide2', wide3 : 'wide3', wide4 : 'wide4', wide5 : 'wide5', wide6 : 'wide6', wide7 : 'wide7', wide8 : 'wide8', wide9 : 'wide9', wide10 : 'wide10', wide11 : 'wide11'};const Paging = { leading : 'leading', centered : 'centered', none : ''};const Orientation = { horizontal : 'horizontal', vertical : 'vertical'};function MainPage(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output;}function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody;}function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo;}function Commands(commandName, params) { this.commandName = commandName; this.params = params;}function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript;}function KeyValue(key, value) { this.key = key; this.value = value;}function Output(cellDesing, orientation, defaultLayout, paging, section, layout, data) { this.cellDesing = cellDesing; this.orientation = orientation; this.defaultLayout = defaultLayout; this.paging = paging; this.section = section; this.layout = layout; this.data = data;}function Section(sectionName, separator) { this.sectionName = sectionName; this.separator = separator;}function Layout(insets, visibleCellsWidthS,visibleCellsWidthM,visibleCellsWidthL, visibleCellsHeight, heightForVisibleCells, cellSize, ratio, constant, horizontalSpacing, verticalSpacing) { this.insets = insets; this.visibleCellsWidthS = visibleCellsWidthS; this.visibleCellsWidthM = visibleCellsWidthM; this.visibleCellsWidthL = visibleCellsWidthL; this.visibleCellsHeight = visibleCellsHeight; this.heightForVisibleCells = heightForVisibleCells; this.cellSize = cellSize; this.ratio = ratio; this.constant = constant; this.horizontalSpacing = horizontalSpacing; this.verticalSpacing = verticalSpacing;}function Insets(top, bottom, left, right) { this.top = top; this.bottom = bottom; this.left = left; this.right = right;}function Size(width, height) { this.width = width; this.height = height;}function Ratio(inRelation, number1, number2) { this.inRelation = inRelation; this.number1 = number1; this.number2 = number2;}function Data(image, title, description, field1, field2, field3, field4, isChapter, link) { this.image = image; this.title = title; this.description = description; this.field1 = field1; this.field2 = field2; this.field3 = field3; this.field4 = field4; this.isChapter = isChapter; this.link = link;}function quickData(link,image,title,field1) { return new Data(image,title,'unknown',field1,'unknown','unknown','unknown',false,link);}function shuffle(a) { var j, x, i; for (i = a.length - 1; i > 0; i--) { j = Math.floor(Math.random() * (i + 1)); x = a[i]; a[i] = a[j]; a[j] = x; } return a;}var savedData = document.getElementById('ketsu-final-data');var parsedJson = JSON.parse(savedData.innerHTML); var output = [];let emptyKeyValue = [new KeyValue('','')]; var dataArray = []; var dataArray2 = []; var topList = document.querySelectorAll('.swiper-slide'); for (var x = 0;x < topList.length; x++) { let list = topList[x]; let title = list.querySelector('.sc-name').innerText; var link = list.querySelector('a').href; link = new ModuleRequest(link,'get',emptyKeyValue,null); var image = list.getAttribute('style').split('\\'')[1]; image = new ModuleRequest(image,'get',emptyKeyValue,null); var finalData = quickData(link,image,title,title,'Unknown'); dataArray.push(finalData); if (parsedJson.request.url.includes('page')) { output[0].data.push(finalData); } finalData = quickData(link,image,title,'Unknown','Unknown'); dataArray2.push(finalData); if (parsedJson.request.url.includes('page')) { output[1].data.push(finalData); } } var topLayout = new Layout(new Insets(0,0,0,0),1,1,2,1,360,new Size(400,400),null,new Size(0,0),0,0); output.push(new Output(CellDesings.Special3,Orientation.horizontal,DefaultLayouts.none,Paging.centered,new Section('',false),topLayout,shuffle(dataArray.slice()))); output.push(new Output(CellDesings.Special1,Orientation.horizontal,DefaultLayouts.triplets,Paging.leading,new Section('Most Seen',true),null,dataArray2)); dataArray = []; topList = document.querySelectorAll('.featured-block')[1].querySelectorAll('li'); for (var x = 0;x < topList.length; x++) { let list = topList[x]; let title = list.querySelector('a').title; var link = list.querySelector('a').href; link = new ModuleRequest(link,'get',emptyKeyValue,null); var image = list.querySelector('img').src; image = new ModuleRequest(image,'get',emptyKeyValue,null); var ep = list.querySelector('.gr-eps').innerText; var type = list.querySelector('.gr-type').innerText; var finalData = new Data(image,title,'unknown',ep,'unknown','unknown','unknown',false,link); dataArray.push(finalData); } output.push(new Output(CellDesings.normal7, Orientation.horizontal, DefaultLayouts.longTripletsDouble, Paging.leading, new Section('Last Episodes', true), null, dataArray)); dataArray = []; topList = document.querySelector('.sb-topanime').querySelectorAll('li'); for (var x = 0;x < topList.length; x++) { let list = topList[x]; let title = list.querySelector('.item-title').innerText; var link = list.querySelector('a').href; link = new ModuleRequest(link,'get',emptyKeyValue,null); var image = list.querySelector('img').src; image = new ModuleRequest(image,'get',emptyKeyValue,null); var type = list.querySelector('.mr10').innerText; var finalData = new Data(image,title,'unknown',type,'Anime','unknown','unknown',false,link); dataArray.push(finalData); } output.push(new Output(CellDesings.wide5, Orientation.horizontal, DefaultLayouts.wideFull, Paging.leading, new Section('Top', true), null, dataArray)); dataArray = []; topList = document.querySelectorAll('.featured-block')[0].querySelectorAll('li'); for (var x = 0;x < topList.length; x++) { let list = topList[x]; let title = list.querySelector('a').title; var link = list.querySelector('a').href; link = new ModuleRequest(link,'get',emptyKeyValue,null); var image = list.querySelector('img').src; image = new ModuleRequest(image,'get',emptyKeyValue,null); var ep = list.querySelector('.gr-eps').innerText; var type = list.querySelector('.gr-type').innerText; var finalData = new Data(image,title,'',ep,'','unknown','unknown',false,link); dataArray.push(finalData); } var testLayout = new Layout(new Insets(0,0,10,10),1,2,3,1,500,new Size(400,400),new Ratio('width',3,10),new Size(0,0),10,10); output.push(new Output(CellDesings.wide6,Orientation.horizontal,DefaultLayouts.doubletsFull,Paging.none,new Section('Featured',true),null,dataArray)); output.push(new Output(CellDesings.wide7, Orientation.horizontal, DefaultLayouts.none, Paging.leading, new Section('', false), testLayout, shuffle(dataArray.slice()))); dataArray = []; topList = document.querySelectorAll('.sb-list-item')[0].querySelectorAll('li'); for (var x = 0;x < topList.length; x++) { let list = topList[x]; let title = list.querySelector('a').title; var link = list.querySelector('a').href; link = new ModuleRequest(link,'get',emptyKeyValue,null); var image = list.querySelector('img').src; image = new ModuleRequest(image,'get',emptyKeyValue,null); var finalData = new Data(image,title,'unknown','Unknown','unknown','unknown','unknown',false,link); dataArray.push(finalData); } output.push(new Output(CellDesings.normal4, Orientation.vertical, DefaultLayouts.longTripletsFull, Paging.none, new Section('Latest Movies', true), null, dataArray ));let MainPageObject = new MainPage(new ModuleRequest('','',emptyKeyValue,null),new Extra([new Commands('',emptyKeyValue)],emptyKeyValue),new JavascriptConfig(false,false,''),output);var finalJson = JSON.stringify(MainPageObject);savedData.innerHTML = finalJson;"
      },
      "output": [
        {
          "cellDesing": "normal1",
          "orientation": "vertical",
          "defaultLayout": "wide",
          "paging": "",
          "section": {
            "sectionName": "",
            "separator": false
          },
          "layout": {
            "insets": {
              "top": 0,
              "bottom": 0,
              "left": 0,
              "right": 0
            },
            "visibleCellsWidthS": 2,
            "visibleCellsWidthM": 2,
            "visibleCellsWidthL": 2,
            "visibleCellsHeight": 2,
            "heightForVisibleCells": 400,
            "cellSize": {
              "width": 300,
              "height": 300
            },
            "ratio": {
              "inRelation": "width",
              "number1": 1,
              "number2": 2
            },
            "constant": {
              "width": 1,
              "height": 2
            },
            "horizontalSpacing": 0,
            "verticalSpacing": 0
          },
          "data": [
            {
              "image": {
                "url": "https://zoro.to/home",
                "method": "get",
                "headers": [
                  {
                    "key": "",
                    "value": ""
                  }
                ],
                "httpBody": null
              },
              "title": "",
              "description": "",
              "field1": "",
              "field2": "",
              "field3": "",
              "field4": "",
              "moduleID": "2384029348",
              "isChapter": false,
              "link": {
                "url": "empty",
                "method": "get",
                "headers": [
                  {
                    "key": "key",
                    "value": "value"
                  }
                ],
                "httpBody": null
              }
            }
          ]
        }
      ]
    }
  ],
  "search": [
    {
      "request": {
        "url": "https://zoro.to/search?keyword=%3Csearched%3E&page=%3Cpage%3E",
        "method": "get",
        "headers": [
          {
            "key": "",
            "value": ""
          }
        ],
        "httpBody": null
      },
      "separator": "+",
      "extra": {
        "commands": [
          {
            "commandName": "",
            "params": [
              {
                "key": "",
                "value": ""
              }
            ]
          }
        ],
        "extraInfo": [
          {
            "key": "",
            "value": ""
          }
        ]
      },
      "javascriptConfig": {
        "removeJavascript": true,
        "loadInWebView": false,
        "javaScript": "const DefaultLayouts = { ultraWideFull : 'ultraWideFull', ultraWide : 'ultraWide', wideFull : 'wideFull', wide : 'wide', wideStrechedFull : 'wideStrechedFull', wideStrechedFullDouble : 'WideStrechedFullDouble', wideStreched : 'wideStreched', wideStrechedDouble : 'wideStrechedDouble', wideStrechedFullList : 'wideStrechedFullList', wideStrechedList : 'wideStrechedList', doublets : 'doublets', doubletsDouble : 'doubletsDouble', doubletsFull : 'doubletsFull', doubletsFullDouble : 'doubletsFullDouble', doubletsConstant : 'doubletsConstant', doubletsDoubleConstant : 'doubletsDoubleConstant', doubletsFullConstant : 'doubletsFullConstant', doubletsFullDoubleConstant : 'doubletsFullDoubleConstant', longDoublets : 'longDoublets', longDoubletsDouble : 'longDoubletsDouble', longDoubletsFull : 'longDoubletsFull', longDoubletsFullDouble : 'longDoubletsFullDouble', longDoubletsConstant : 'longDoubletsConstant', longDoubletsDoubleConstant : 'longDoubletsDoubleConstant', longDoubletsFullConstant : 'longDoubletsFullConstant', longDoubletsFullDoubleConstant : 'longDoubletsFullDoubleConstant', triplets : 'triplets', tripletsDouble : 'tripletsDouble', tripletsFull : 'tripletsFull', tripletsFullDouble : 'tripletsFullDouble', tripletsConstant : 'tripletsConstant', tripletsDoubleConstant : 'tripletsDoubleConstant', tripletsFullConstant : 'tripletsFullConstant', tripletsFullDoubleConstant : 'tripletsFullDoubleConstant', longTriplets : 'longTriplets', longTripletsDouble : 'longTripletsDouble', longTripletsFull : 'longTripletsFull', longTripletsFullDouble : 'longTripletsFullDouble', longTripletsConstant : 'longTripletsConstant', longTripletsDoubleConstant : 'longTripletsDoubleConstant', longTripletsFullConstant : 'longTripletsFullConstant', longTripletsFullDoubleConstant : 'longTripletsFullDoubleConstant', none: '' }; const CellDesings = { Special1 : 'Special1', Special2 : 'Special2', Special3 : 'Special3', small1 : 'small1', small2 : 'small2', normal1 : 'normal1', normal2 : 'normal2', normal3 : 'normal3', normal4 : 'normal4', normal5 : 'normal5', normal6 : 'normal6', normal7 : 'normal7', wide1 : 'wide1', wide2 : 'wide2', wide3 : 'wide3', wide4 : 'wide4', wide5 : 'wide5', wide6 : 'wide6', wide7 : 'wide7', wide8 : 'wide8', wide9 : 'wide9', wide10 : 'wide10', wide11 : 'wide11' }; const Paging = { leading : 'leading', centered : 'centered', none : '' }; const Orientation = { horizontal : 'horizontal', vertical : 'vertical' }; function Search(request,extra,separator,javascriptConfig,output) { this.request = request; this.extra = extra; this.separator = separator; this.javascriptConfig = javascriptConfig; this.output = output; } function ModuleRequest(url,method,headers,httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody; } function Extra(commands,extraInfo) { this.commands = commands; this.extraInfo = extraInfo; } function Commands(commandName,params) { this.commandName = commandName; this.params = params; } function JavascriptConfig(removeJavascript,loadInWebView,javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript; } function KeyValue(key,value) { this.key = key; this.value = value; } function Output(cellDesing,orientation,defaultLayout,paging,section,layout,data) { this.cellDesing = cellDesing; this.orientation = orientation; this.defaultLayout = defaultLayout; this.paging = paging; this.section = section; this.layout = layout; this.data = data; } function Section(sectionName,separator) { this.sectionName = sectionName; this.separator = separator; } function Layout(insets, visibleCellsWidthS,visibleCellsWidthM,visibleCellsWidthL, visibleCellsHeight, heightForVisibleCells, cellSize, ratio, constant, horizontalSpacing, verticalSpacing) { this.insets = insets; this.visibleCellsWidthS = visibleCellsWidthS; this.visibleCellsWidthM = visibleCellsWidthM; this.visibleCellsWidthL = visibleCellsWidthL; this.visibleCellsHeight = visibleCellsHeight; this.heightForVisibleCells = heightForVisibleCells; this.cellSize = cellSize; this.ratio = ratio; this.constant = constant; this.horizontalSpacing = horizontalSpacing; this.verticalSpacing = verticalSpacing; } function Insets(top,bottom,left,right) { this.top = top; this.bottom = bottom; this.left = left; this.right = right; } function Size(width,height) { this.width = width; this.height = height; } function Ratio(inRelation,number1,number2) { this.inRelation = inRelation; this.number1 = number1; this.number2 = number2; } function Data(image,title,description,field1,field2,field3,field4,isChapter,link) { this.image = image; this.title = title; this.description = description; this.field1 = field1; this.field2 = field2; this.field3 = field3; this.field4 = field4; this.isChapter = isChapter; this.link = link; }function quickData(link,image,title,field1) { return new Data(image,title,'unknown',field1,'unknown','unknown','unknown',false,link); } function shuffle(a) { var j, x, i; for (i = a.length - 1; i > 0; i--) { j = Math.floor(Math.random() * (i + 1)); x = a[i]; a[i] = a[j]; a[j] = x; } return a; } var savedData = document.getElementById('ketsu-final-data'); var parsedJson = JSON.parse(savedData.innerHTML); let output = []; let emptyKeyValue = [new KeyValue('','')]; var lastAdded = document.querySelector('.grid-item').querySelectorAll('li'); let lastAddedArray = []; for (var x = 0; x < lastAdded.length;x++) { try { let list = lastAdded[x]; let title = list.querySelector('a').title; var link = list.querySelector('a').href; link = new ModuleRequest(link,'get',emptyKeyValue,null); var image = list.querySelector('img').src; image = new ModuleRequest(image,'get',emptyKeyValue,null); var ep = list.querySelector('.gr-eps').innerText; var type = list.querySelector('.gr-type').innerText; var finalData = new Data(image,title,ep,type,'unknown','unknown','unknown',false,link); lastAddedArray.push(finalData); } catch (e) {} } var testLayout = new Layout(new Insets(10,10,10,10),1,2,3,1,500,new Size(400,400),new Ratio('width',4,11),new Size(0,0),10,10); output.push(new Output(CellDesings.wide11,Orientation.vertical,DefaultLayouts.none,Paging.none,new Section('',false),testLayout,lastAddedArray));; let searchPageObject = new Search(new ModuleRequest('','',emptyKeyValue,null),new Extra([new Commands('',emptyKeyValue)],emptyKeyValue),'',new JavascriptConfig(false,false,''),output); var finalJson = JSON.stringify(searchPageObject); savedData.innerHTML = finalJson;"
      },
      "output": [
        {
          "cellDesing": "normal1",
          "orientation": "vertical",
          "defaultLayout": "wide",
          "paging": "",
          "section": {
            "sectionName": "",
            "separator": false
          },
          "layout": {
            "insets": {
              "top": 0,
              "bottom": 0,
              "left": 0,
              "right": 0
            },
            "visibleCellsWidthS": 2,
            "visibleCellsWidthM": 2,
            "visibleCellsWidthL": 2,
            "visibleCellsHeight": 2,
            "heightForVisibleCells": 400,
            "cellSize": {
              "width": 300,
              "height": 300
            },
            "ratio": {
              "inRelation": "width",
              "number1": 1,
              "number2": 2
            },
            "constant": {
              "width": 1,
              "height": 2
            },
            "horizontalSpacing": 0,
            "verticalSpacing": 0
          },
          "data": [
            {
              "image": {
                "url": "https://zoro.to/home",
                "method": "get",
                "headers": [
                  {
                    "key": "",
                    "value": ""
                  }
                ],
                "httpBody": null
              },
              "title": "",
              "description": "",
              "field1": "",
              "field2": "",
              "field3": "",
              "field4": "",
              "moduleID": "2384029348",
              "isChapter": false,
              "link": {
                "url": "empty",
                "method": "get",
                "headers": [
                  {
                    "key": "key",
                    "value": "value"
                  }
                ],
                "httpBody": null
              }
            }
          ]
        }
      ]
    }
  ],
  "info": [
    {
      "request": {
        "url": "empty",
        "method": "get",
        "headers": [
          {
            "key": "key",
            "value": "value"
          }
        ],
        "httpBody": null
      },
      "extra": {
        "commands": [
          {
            "commandName": "",
            "params": [
              {
                "key": "",
                "value": ""
              }
            ]
          }
        ],
        "extraInfo": [
          {
            "key": "",
            "value": ""
          }
        ]
      },
      "javascriptConfig": {
        "removeJavascript": true,
        "loadInWebView": false,
        "javaScript": "function Info(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output;}function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody;}function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo;}function Commands(commandName, params) { this.commandName = commandName; this.params = params;}function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript;}function KeyValue(key, value) { this.key = key; this.value = value;}function Chapter(chapName, link,openInWebView) { this.chapName = chapName; this.link = link; this.openInWebView = openInWebView;}function Output(image, title, link, description, genres, field1, field2, field3, field4, chapters) { this.image = image; this.link = link; this.title = title; this.description = description; this.genres = genres; this.field1 = field1; this.field2 = field2; this.field3 = field3; this.field4 = field4; this.chapters = chapters;}function getStuff(array,match) { for (var x = 0 ; x< array.length;x++) { let data = array[x].innerText; if (data.includes(match)) { return data.replace(match,'').trim(); } } }function getHtmlStuff(array,match) { for (var x = 0 ; x< array.length;x++) { let data = array[x].innerText; if (data.includes(match)) { return array[x]; } }}var savedData = document.getElementById('ketsu-final-data');var parsedJson = JSON.parse(savedData.innerHTML);let emptyKeyValue = [new KeyValue('', '')];var episodes = [];var type = '';var status = '';var genres = [];var desc = '';var image = '';var title = '';image = document.querySelector('.dc-thumb').querySelector('img').src;image = new ModuleRequest(image,'get',emptyKeyValue,null);title = document.querySelector('.dc-title').innerHTML;desc = document.querySelector('.dci-desc').innerText;type = document.querySelector('.dcis-04').innerText.replace('Type: ', '');status = document.querySelector('.dcis-03').innerText.replace('Status: ', '');var genresArray = document.querySelector('.dcis-01').querySelectorAll('a');if (genresArray.length < 1) { genres = [''];}for (var x = 0; x < genresArray.length; x++) { var gen = genresArray[x].innerHTML; genres.push(gen);}var epsArray = document.querySelector('#episodes-sv-1').querySelectorAll('li');for (var x = 0; x < epsArray.length; x++) { var ep = epsArray[x].querySelector('a').href; let chapter = new Chapter(epsArray[x].querySelector('.sli-name').querySelector('a').innerHTML,new ModuleRequest('https://https://zoro.to'%20+%20ep,'get,emptyKeyValue,null),false); episodes.push(chapter);}episodes.reverse();let infoPageObject = new Info(new ModuleRequest('', '', emptyKeyValue, null), new Extra([new Commands('', emptyKeyValue)], emptyKeyValue), new JavascriptConfig(false, false, ''), new Output(image, title, parsedJson.request, desc, genres, status, 'Anime', type, 'Eps: ' + episodes.length, episodes));var finalJson = JSON.stringify(infoPageObject);savedData.innerHTML = finalJson;"
      },
      "output": {
        "image": {
          "url": "https://zoro.to/home",
          "method": "get",
          "headers": [
            {
              "key": "",
              "value": ""
            }
          ],
          "httpBody": null
        },
        "link": {
          "url": "https://zoro.to/home",
          "method": "get",
          "headers": [
            {
              "key": "",
              "value": ""
            }
          ],
          "httpBody": null
        },
        "title": "",
        "description": "",
        "moduleID": "234234823",
        "genres": [
          ""
        ],
        "field1": "",
        "field2": "",
        "field3": "",
        "field4": "",
        "chapters": [
          {
            "chapName": "",
            "openInWebView": false,
            "link": {
              "url": "empty",
              "method": "get",
              "headers": [
                {
                  "key": "key",
                  "value": "value"
                }
              ],
              "httpBody": null
            }
          }
        ]
      }
    }
  ],
  "chapters": [
    {
      "request": {
        "url": "empty",
        "method": "get",
        "headers": [
          {
            "key": "key",
            "value": "value"
          }
        ],
        "httpBody": null
      },
      "extra": {
        "commands": [
          {
            "commandName": "",
            "params": [
              {
                "key": "",
                "value": ""
              }
            ]
          }
        ],
        "extraInfo": [
          {
            "key": "",
            "value": ""
          }
        ]
      },
      "javascriptConfig": {
        "removeJavascript": true,
        "loadInWebView": false,
        "javaScript": " function Chapters(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output; } function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody; } function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo; } function Commands(commandName, params) { this.commandName = commandName; this.params = params; } function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript; } function KeyValue(key, value) { this.key = key; this.value = value; } function Output( videos, images, text) { this.videos = videos; this.images = images; this.text = text; } function Videos(needsResolver, rawVideo) { this.needsResolver = needsResolver; this.rawVideo = rawVideo; } function NeedsResolver(resolverIdentifier, link) { this.resolverIdentifier = resolverIdentifier; this.link = link; } function RawVideo(video) { this.video = video; } function Video(videoQuality, videoLink) { this.videoQuality = videoQuality; this.videoLink = videoLink; } function Images(images) { this.images = images; } function Text(text) { this.text = text; } var output = []; var savedData = document.getElementById('ketsu-final-data'); var parsedJson = JSON.parse(savedData.innerHTML); var emptyKeyValue = [new KeyValue('Referer', 'https://zoro.to/home')]; var ctk = ''; var epId = parsedJson.request.url.split('?ep=')[1]; var ps = document.querySelectorAll('p'); var extraInfo = [new KeyValue('count','0')]; for (var x = 0; x < ps.length; x++) { if (ps[x].innerText.includes('var ctk =')) { ctk = ps[x].innerText.split('\\'')[1]; break; } } var httpBody = 'episode_id=' + epId + '&ctk=' + ctk; extraInfo.push(new KeyValue('httpBody',httpBody)); var nextRequest = ''; let options = document.querySelector('#info_player').querySelectorAll('option'); for (var x = 0; x < options.length; x++) { let option = options[x].getAttribute('sv'); if (x == 0) { nextRequest = 'https://zoro.to/ajax/anime/episode?id=${serv[%27Streamtape%27]}`'get' + option; } else { extraInfo.push(new KeyValue('server'+ (x - 1),'https://zoro.to/ajax/anime/episode?id=${serv[%27Streamtape%27]}`'get' + option)); } } let emptyExtra = new Extra([new Commands('', emptyKeyValue)], extraInfo); var chaptersObject = new Chapters(new ModuleRequest(nextRequest, 'post', emptyKeyValue, httpBody), emptyExtra, new JavascriptConfig(false, false, ''), new Output(new Videos([], []), null, null)); var finalJson = JSON.stringify(chaptersObject); savedData.innerText = finalJson;"
      },
      "output": {
        "moduleID": "234234823",
        "videos": {
          "needsResolver": [
            {
              "resolverIdentifier": "",
              "link": {
                "url": "https://zoro.to/home”,
                "method": "get",
                "headers": [
                  {
                    "key": "key",
                    "value": "value"
                  }
                ],
                "httpBody": null
              }
            }
          ],
          "rawVideo": [
            {
              "video": [
                {
                  "videoQuality": "720",
                  "videoLink": {
                    "url": "http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4",
                    "method": "get",
                    "headers": [
                      {
                        "key": "key",
                        "value": "value"
                      }
                    ],
                    "httpBody": null
                  }
                }
              ]
            }
          ]
        },
        "images": [
          {
            "url": "empty",
            "method": "get",
            "headers": [
              {
                "key": "key",
                "value": "value"
              }
            ],
            "httpBody": null
          }
        ],
        "text": {
          "text": ""
        }
      }
    },
    {
      "request": {
        "url": "empty",
        "method": "get",
        "headers": [
          {
            "key": "key",
            "value": "value"
          }
        ],
        "httpBody": null
      },
      "extra": {
        "commands": [
          {
            "commandName": "",
            "params": [
              {
                "key": "",
                "value": ""
              }
            ]
          }
        ],
        "extraInfo": [
          {
            "key": "",
            "value": ""
          }
        ]
      },
      "javascriptConfig": {
        "removeJavascript": true,
        "loadInWebView": false,
        "javaScript": " function Chapters(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output; } function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody; } function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo; } function Commands(commandName, params) { this.commandName = commandName; this.params = params; } function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript; } function KeyValue(key, value) { this.key = key; this.value = value; } function Output( videos, images, text) { this.videos = videos; this.images = images; this.text = text; } function Videos(needsResolver, rawVideo) { this.needsResolver = needsResolver; this.rawVideo = rawVideo; } function NeedsResolver(resolverIdentifier, link) { this.resolverIdentifier = resolverIdentifier; this.link = link; } function RawVideo(video) { this.video = video; } function Video(videoQuality, videoLink) { this.videoQuality = videoQuality; this.videoLink = videoLink; } function Images(images) { this.images = images; } function Text(text) { this.text = text; } function getValueFromKey(keys,key) { for (var x = 0; x < keys.length; x++) { let tKey = keys[x]; if (tKey.key == key) { return tKey.value; } } } var savedData = document.getElementById('ketsu-final-data'); var parsedJson = JSON.parse(savedData.innerText); var output = parsedJson.output.videos; var emptyKeyValue = [new KeyValue('', '')]; var extraInfo = parsedJson.extra.extraInfo; var server = parsedJson.request.url.split('odes_v2?s=')[1]; var actualCount = getValueFromKey(extraInfo,'count'); if (actualCount == 0) { output = new Videos([],[]); } let data = document.querySelector('script').innerText.replace('/*','').replace('*/',''); var httpBody = getValueFromKey(extraInfo,'httpBody'); var nextRequest = getValueFromKey(extraInfo,'server' + actualCount); let parsedResponse = JSON.parse(data); let link = parsedResponse.value.split('\\\"')[1]; let videoHeaders = [new KeyValue('Referer','https://zoro.to/home/'), new KeyValue('Accept','text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3'),new KeyValue('accept-language','en-us')]; output.needsResolver.push(new NeedsResolver(server, new ModuleRequest(encodeURIComponent(link), 'get', videoHeaders, null))); extraInfo[0].value = '' + (parseInt(actualCount) + 1); if (nextRequest == undefined) { nextRequest = ''; for (var x = 0; x < output.needsResolver.length; x++) { let vid = decodeURIComponent(output.needsResolver[x].link.url); if (!vid.includes('https:')) { output.needsResolver[x].link.url = 'https:' + vid; } else { output.needsResolver[x].link.url = vid; } } } let emptyExtra = new Extra([new Commands('', emptyKeyValue)], extraInfo); var chaptersObject = new Chapters(new ModuleRequest(nextRequest, 'post', videoHeaders, httpBody), emptyExtra, new JavascriptConfig(false, false, ''), new Output(output, null, null)); var finalJson = JSON.stringify(chaptersObject); savedData.innerText = finalJson;"
      },
      "output": {
        "moduleID": "234234823",
        "videos": {
          "needsResolver": [
            {
              "resolverIdentifier": "",
              "link": {
                "url": "https://zoro.to/home",
                "method": "get",
                "headers": [
                  {
                    "key": "key",
                    "value": "value"
                  }
                ],
                "httpBody": null
              }
            }
          ],
          "rawVideo": [
            {
              "video": [
                {
                  "videoQuality": "720",
                  "videoLink": {
                    "url": "http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4",
                    "method": "get",
                    "headers": [
                      {
                        "key": "key",
                        "value": "value"
                      }
                    ],
                    "httpBody": null
                  }
                }
              ]
            }
          ]
        },
        "images": [
          {
            "url": "empty",
            "method": "get",
            "headers": [
              {
                "key": "key",
                "value": "value"
              }
            ],
            "httpBody": null
          }
        ],
        "text": {
          "text": ""
        }
      }
    }
  ],
  "moduleResolvers": [
    {
      "resolverInfo": {
        "resolverName": "",
        "nameMatches": [
          ""
        ],
        "developer": "",
        "moduleID": "",
        "resolverVersion": 1,
        "baseURL": ""
      },
      "resolver": [
        {
          "request": {
            "url": "empty",
            "method": "get",
            "headers": [
              {
                "key": "key",
                "value": "value"
              }
            ],
            "httpBody": null
          },
          "extra": {
            "commands": [
              {
                "commandName": "",
                "params": [
                  {
                    "key": "",
                    "value": ""
                  }
                ]
              }
            ],
            "extraInfo": [
              {
                "key": "",
                "value": ""
              }
            ]
          },
          "javascriptConfig": {
            "removeJavascript": false,
            "loadInWebView": false,
            "javaScript": ""
          },
          "output": {
            "moduleID": "234234823",
            "video": [
              {
                "videoQuality": "720",
                "videoLink": {
                  "url": "http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4",
                  "method": "get",
                  "headers": [
                    {
                      "key": "key",
                      "value": "value"
                    }
                  ],
                  "httpBody": null
                }
              }
            ]
          }
        }
      ]
    }
  ],
  "responseCodeFunctions": [
    {
      "code": 0,
      "msgTitle": "",
      "msgBody": "",
      "type": "normal",
      "functions": [
        {
          "request": {
            "url": "empty",
            "method": "get",
            "headers": [
              {
                "key": "key",
                "value": "value"
              }
            ],
            "httpBody": null
          },
          "extra": {
            "commands": [
              {
                "commandName": "",
                "params": [
                  {
                    "key": "",
                    "value": ""
                  }
                ]
              }
            ],
            "extraInfo": [
              {
                "key": "",
                "value": ""
              }
            ]
          },
          "javascriptConfig": {
            "removeJavascript": true,
            "loadInWebView": false,
            "javaScript": ""
          }
        }
      ]
    }
  ],
  "helperFunctions": [
    {
      "functionName": "example",
      "msgTitle": "",
      "msgBody": "",
      "type": "normal",
      "functions": [
        {
          "request": {
            "url": "empty",
            "method": "get",
            "headers": [
              {
                "key": "key",
                "value": "value"
              }
            ],
            "httpBody": null
          },
          "extra": {
            "commands": [
              {
                "commandName": "",
                "params": [
                  {
                    "key": "",
                    "value": ""
                  }
                ]
              }
            ],
            "extraInfo": [
              {
                "key": "",
                "value": ""
              }
            ]
          },
          "javascriptConfig": {
            "removeJavascript": true,
            "loadInWebView": false,
            "javaScript": ""
          }
        }
      ]
    }
  ]
}
