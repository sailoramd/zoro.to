{
  "moduleInfo": {
    "moduleName": "AnimePahe",
    "moduleInitials": "ANPH",
    "moduleDesc": "Module to Get Data From AnimePahe",
    "developer": "Noah G",
    "moduleID": "46239462794617941",
    "moduleImage": "https://pm1.narvii.com/6291/55276042f937ffe65cd921d5671aa3a0daa30ed5_hq.jpg",
    "moduleVersion": 1,
    "moduleLenguage": "ENG",
    "moduleType": "Video",
    "baseURL": "https://zoro.to/home",
    "moduleDeveloperSite": "https://mprotmod.github.io/Modules-KETSU/index.html",
    "UpdateSite": "https://raw.githubusercontent.com/mprotmod/Modules-KETSU/main/Module%20Parser%20KETSU/AnimePahe/module.json",
    "preferedServer": "KWIK-1080P-JPN",
    "preferedDownloadServer": "KWIK-1080P-JPN",
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
        "url": "https://animepahe.com/api?m=airing&l=12&page=1",
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
        "javaScript": " const DefaultLayouts = { ultraWideFull: 'ultraWideFull', ultraWide: 'ultraWide', wideFull: 'wideFull', wide: 'wide', wideStrechedFull: 'wideStrechedFull', wideStrechedFullDouble: 'WideStrechedFullDouble', wideStreched: 'wideStreched', wideStrechedDouble: 'wideStrechedDouble', wideStrechedFullList: 'wideStrechedFullList', wideStrechedList: 'wideStrechedList', doublets: 'doublets', doubletsDouble: 'doubletsDouble', doubletsFull: 'doubletsFull', doubletsFullDouble: 'doubletsFullDouble', doubletsConstant: 'doubletsConstant', doubletsDoubleConstant: 'doubletsDoubleConstant', doubletsFullConstant: 'doubletsFullConstant', doubletsFullDoubleConstant: 'doubletsFullDoubleConstant', longDoublets: 'longDoublets', longDoubletsDouble: 'longDoubletsDouble', longDoubletsFull: 'longDoubletsFull', longDoubletsFullDouble: 'longDoubletsFullDouble', longDoubletsConstant: 'longDoubletsConstant', longDoubletsDoubleConstant: 'longDoubletsDoubleConstant', longDoubletsFullConstant: 'longDoubletsFullConstant', longDoubletsFullDoubleConstant: 'longDoubletsFullDoubleConstant', triplets: 'triplets', tripletsDouble: 'tripletsDouble', tripletsFull: 'tripletsFull', tripletsFullDouble: 'tripletsFullDouble', tripletsConstant: 'tripletsConstant', tripletsDoubleConstant: 'tripletsDoubleConstant', tripletsFullConstant: 'tripletsFullConstant', tripletsFullDoubleConstant: 'tripletsFullDoubleConstant', longTriplets: 'longTriplets', longTripletsDouble: 'longTripletsDouble', longTripletsFull: 'longTripletsFull', longTripletsFullDouble: 'longTripletsFullDouble', longTripletsConstant: 'longTripletsConstant', longTripletsDoubleConstant: 'longTripletsDoubleConstant', longTripletsFullConstant: 'longTripletsFullConstant', longTripletsFullDoubleConstant: 'longTripletsFullDoubleConstant', none: ''};const CellDesings = { Special1: 'Special1', Special2: 'Special2', Special3: 'Special3', CELLHelperText: 'CELLHelperText', small1: 'small1', small2: 'small2', normal1: 'normal1', normal2: 'normal2', normal3: 'normal3', normal4: 'normal4', normal5: 'normal5', normal6: 'normal6', normal7: 'normal7', wide1: 'wide1', wide2: 'wide2', wide3: 'wide3', wide4: 'wide4', wide5: 'wide5', wide6: 'wide6', wide7: 'wide7', wide8: 'wide8', wide9: 'wide9', wide10: 'wide10', wide11: 'wide11'};const Paging = { leading: 'leading', centered: 'centered', none: ''};const Orientation = { horizontal: 'horizontal', vertical: 'vertical'};function MainPage(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output;}function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody;}function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo;}function Commands(commandName, params) { this.commandName = commandName; this.params = params;}function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript;}function KeyValue(key, value) { this.key = key; this.value = value;}function Output(cellDesing, orientation, defaultLayout, paging, section, layout, data) { this.cellDesing = cellDesing; this.orientation = orientation; this.defaultLayout = defaultLayout; this.paging = paging; this.section = section; this.layout = layout; this.data = data;}function Section(sectionName, separator) { this.sectionName = sectionName; this.separator = separator;}function Layout(insets, visibleCellsWidthS, visibleCellsWidthM, visibleCellsWidthL, visibleCellsHeight, heightForVisibleCells, cellSize, ratio, constant, horizontalSpacing, verticalSpacing) { this.insets = insets; this.visibleCellsWidthS = visibleCellsWidthS; this.visibleCellsWidthM = visibleCellsWidthM; this.visibleCellsWidthL = visibleCellsWidthL; this.visibleCellsHeight = visibleCellsHeight; this.heightForVisibleCells = heightForVisibleCells; this.cellSize = cellSize; this.ratio = ratio; this.constant = constant; this.horizontalSpacing = horizontalSpacing; this.verticalSpacing = verticalSpacing;}function Insets(top, bottom, left, right) { this.top = top; this.bottom = bottom; this.left = left; this.right = right;}function Size(width, height) { this.width = width; this.height = height;}function Ratio(inRelation, number1, number2) { this.inRelation = inRelation; this.number1 = number1; this.number2 = number2;}function Data(image, title, description, field1, field2, field3, field4, isChapter, link, openInWebView) { this.image = image; this.title = title; this.description = description; this.field1 = field1; this.field2 = field2; this.field3 = field3; this.field4 = field4; this.isChapter = isChapter; this.link = link; this.openInWebView = openInWebView;}function quickData(link, image, title, field1) { return new Data(image, title, 'unknown', field1, 'unknown', 'unknown', 'unknown', false, link);}function shuffle(a) { var j, x, i; for (i = a.length - 1; i > 0; i--) { j = Math.floor(Math.random() * (i + 1)); x = a[i]; a[i] = a[j]; a[j] = x; } return a;}var savedData = document.getElementById('ketsu-final-data');var parsedJson = JSON.parse(savedData.innerHTML);let output = [];let emptyKeyValue = [new KeyValue('', '')];let dataArray = [];let dataArray2 = [];let dataArray3 = [];var topLayout = new Layout(new Insets(0, 0, 0, 0), 1, 2, 3, 1, 500, new Size(400, 400), new Ratio('width', 1, 1), new Size(0, 0), 0, 0);var scriptdata = JSON.parse(document.querySelector('script').innerText.replace('/*', '').replace('*/', '')).data;for (var x = 0; x < scriptdata.length; x++) { let image = scriptdata[x].snapshot; let link = 'https://pahe.win/a/' + scriptdata[x].anime_id + '?id=' + scriptdata[x].anime_id; image = new ModuleRequest(image, 'get', emptyKeyValue, null); link = new ModuleRequest(link, 'get', emptyKeyValue, null); let episode = 'Episode ' + scriptdata[x].episode; let title = scriptdata[x].anime_title; dataArray.push(new Data(image, title, 'desc', title, episode, 'field3', 'field4', false, link)); dataArray2.push(new Data(image, title, episode, 'Anime', episode, 'field3', 'field4', false, link)); dataArray3.push(new Data(image, title, episode, episode, episode, 'field3', 'field4', false, link));}output.push(new Output(CellDesings.Special3, Orientation.horizontal, DefaultLayouts.none, Paging.centered, new Section('', false), topLayout, dataArray));output.push(new Output(CellDesings.Special1, Orientation.horizontal, DefaultLayouts.triplets, Paging.leading, new Section('This week', true), null, shuffle(dataArray2)));output.push(new Output(CellDesings.normal2,Orientation.horizontal,DefaultLayouts.longTripletsDouble,Paging.leading,new Section('Last Episodes',true),null,dataArray3)); var testLayout = new Layout(new Insets(10, 10, 10, 10), 1, 3, 5, 1, 500, new Size(400, 400), new Ratio('width', 11, 10), new Size(-60, 0), 10, 10);output.push(new Output(CellDesings.Special2, Orientation.horizontal, DefaultLayouts.none, Paging.leading, new Section('Latest - Page 1', true), testLayout, shuffle(dataArray)));let MainPageObject = new MainPage(new ModuleRequest('https://animepahe.com/api?m=airing&l=12&page=2', 'get', emptyKeyValue, null), new Extra([new Commands('', emptyKeyValue)], emptyKeyValue), new JavascriptConfig(true, false, ''), output);var finalJson = JSON.stringify(MainPageObject);savedData.innerHTML = finalJson;"
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
                "url": "",
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
              "openInWebView" : false,
              "isChapter": false,
              "link": {
                "url": "",
                "method": "",
                "headers": [
                  {
                    "key": "",
                    "value": ""
                  }
                ],
                "httpBody": null
              }
            }
          ]
        }
      ]
    },{
      "request": {
        "url": "",
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
        "javaScript": " const DefaultLayouts = { ultraWideFull: 'ultraWideFull', ultraWide: 'ultraWide', wideFull: 'wideFull', wide: 'wide', wideStrechedFull: 'wideStrechedFull', wideStrechedFullDouble: 'WideStrechedFullDouble', wideStreched: 'wideStreched', wideStrechedDouble: 'wideStrechedDouble', wideStrechedFullList: 'wideStrechedFullList', wideStrechedList: 'wideStrechedList', doublets: 'doublets', doubletsDouble: 'doubletsDouble', doubletsFull: 'doubletsFull', doubletsFullDouble: 'doubletsFullDouble', doubletsConstant: 'doubletsConstant', doubletsDoubleConstant: 'doubletsDoubleConstant', doubletsFullConstant: 'doubletsFullConstant', doubletsFullDoubleConstant: 'doubletsFullDoubleConstant', longDoublets: 'longDoublets', longDoubletsDouble: 'longDoubletsDouble', longDoubletsFull: 'longDoubletsFull', longDoubletsFullDouble: 'longDoubletsFullDouble', longDoubletsConstant: 'longDoubletsConstant', longDoubletsDoubleConstant: 'longDoubletsDoubleConstant', longDoubletsFullConstant: 'longDoubletsFullConstant', longDoubletsFullDoubleConstant: 'longDoubletsFullDoubleConstant', triplets: 'triplets', tripletsDouble: 'tripletsDouble', tripletsFull: 'tripletsFull', tripletsFullDouble: 'tripletsFullDouble', tripletsConstant: 'tripletsConstant', tripletsDoubleConstant: 'tripletsDoubleConstant', tripletsFullConstant: 'tripletsFullConstant', tripletsFullDoubleConstant: 'tripletsFullDoubleConstant', longTriplets: 'longTriplets', longTripletsDouble: 'longTripletsDouble', longTripletsFull: 'longTripletsFull', longTripletsFullDouble: 'longTripletsFullDouble', longTripletsConstant: 'longTripletsConstant', longTripletsDoubleConstant: 'longTripletsDoubleConstant', longTripletsFullConstant: 'longTripletsFullConstant', longTripletsFullDoubleConstant: 'longTripletsFullDoubleConstant', none: '' }; const CellDesings = { Special1: 'Special1', Special2: 'Special2', Special3: 'Special3', CELLHelperText: 'CELLHelperText', small1: 'small1', small2: 'small2', normal1: 'normal1', normal2: 'normal2', normal3: 'normal3', normal4: 'normal4', normal5: 'normal5', normal6: 'normal6', normal7: 'normal7', wide1: 'wide1', wide2: 'wide2', wide3: 'wide3', wide4: 'wide4', wide5: 'wide5', wide6: 'wide6', wide7: 'wide7', wide8: 'wide8', wide9: 'wide9', wide10: 'wide10', wide11: 'wide11' }; const Paging = { leading: 'leading', centered: 'centered', none: '' }; const Orientation = { horizontal: 'horizontal', vertical: 'vertical' }; function MainPage(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output; } function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody; } function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo; } function Commands(commandName, params) { this.commandName = commandName; this.params = params; } function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript; } function KeyValue(key, value) { this.key = key; this.value = value; } function Output(cellDesing, orientation, defaultLayout, paging, section, layout, data) { this.cellDesing = cellDesing; this.orientation = orientation; this.defaultLayout = defaultLayout; this.paging = paging; this.section = section; this.layout = layout; this.data = data; } function Section(sectionName, separator) { this.sectionName = sectionName; this.separator = separator; } function Layout(insets, visibleCellsWidthS, visibleCellsWidthM, visibleCellsWidthL, visibleCellsHeight, heightForVisibleCells, cellSize, ratio, constant, horizontalSpacing, verticalSpacing) { this.insets = insets; this.visibleCellsWidthS = visibleCellsWidthS; this.visibleCellsWidthM = visibleCellsWidthM; this.visibleCellsWidthL = visibleCellsWidthL; this.visibleCellsHeight = visibleCellsHeight; this.heightForVisibleCells = heightForVisibleCells; this.cellSize = cellSize; this.ratio = ratio; this.constant = constant; this.horizontalSpacing = horizontalSpacing; this.verticalSpacing = verticalSpacing; } function Insets(top, bottom, left, right) { this.top = top; this.bottom = bottom; this.left = left; this.right = right; } function Size(width, height) { this.width = width; this.height = height; } function Ratio(inRelation, number1, number2) { this.inRelation = inRelation; this.number1 = number1; this.number2 = number2; } function Data(image, title, description, field1, field2, field3, field4, isChapter, link, openInWebView) { this.image = image; this.title = title; this.description = description; this.field1 = field1; this.field2 = field2; this.field3 = field3; this.field4 = field4; this.isChapter = isChapter; this.link = link; this.openInWebView = openInWebView; } function quickData(link, image, title, field1) { return new Data(image, title, 'unknown', field1, 'unknown', 'unknown', 'unknown', false, link); } function shuffle(a) { var j, x, i; for (i = a.length - 1; i > 0; i--) { j = Math.floor(Math.random() * (i + 1)); x = a[i]; a[i] = a[j]; a[j] = x; } return a; } var savedData = document.getElementById('ketsu-final-data'); var parsedJson = JSON.parse(savedData.innerHTML); let output = parsedJson.output; let emptyKeyValue = [new KeyValue('', '')]; let dataArray = []; let dataArray2 = []; var topLayout = new Layout(new Insets(0, 0, 0, 0), 1, 2, 3, 1, 500, new Size(400, 400), new Ratio('width', 1, 1), new Size(0, 0), 0, 0); var scriptdata = JSON.parse(document.querySelector('script').innerText.replace('/*', '').replace('*/', '')).data; for (var x = 0; x < scriptdata.length; x++) { let image = scriptdata[x].snapshot; let link = 'https://pahe.win/a/' + scriptdata[x].anime_id + '?id=' + scriptdata[x].anime_id; image = new ModuleRequest(image, 'get', emptyKeyValue, null); link = new ModuleRequest(link, 'get', emptyKeyValue, null); let episode = 'Episode ' + scriptdata[x].episode; let title = scriptdata[x].anime_title; dataArray.push(new Data(image, title, episode, 'Anime', episode, 'field3', 'field4', false, link)); dataArray2.push(new Data(image, title, episode, 'Anime', episode, 'field3', 'field4', false, link)); output[0].data.push(new Data(image, title, 'desc', title, episode, 'field3', 'field4', false, link)); output[1].data.push(new Data(image, title, 'desc', episode, episode, 'field3', 'field4', false, link)); } output[0].data = shuffle(output[0].data); var testLayout = new Layout(new Insets(10, 10, 10, 10), 1, 3, 5, 1, 500, new Size(500, 500), new Ratio('width', 11, 10), new Size(-60, 0), 10, 10); output.push(new Output(CellDesings.wide2, Orientation.horizontal, DefaultLayouts.wideStrechedList, Paging.leading, new Section('Latest 2', true), null, shuffle(dataArray2))); output.push(new Output(CellDesings.normal4, Orientation.horizontal, DefaultLayouts.longDoubletsFull, Paging.none, new Section('More', true), null, dataArray)); let MainPageObject = new MainPage(new ModuleRequest('', 'get', emptyKeyValue, null), new Extra([new Commands('', emptyKeyValue)], emptyKeyValue), new JavascriptConfig(true, false, ''), output); var finalJson = JSON.stringify(MainPageObject); savedData.innerHTML = finalJson;"
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
                "url": "",
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
              "openInWebView" : false,
              "isChapter": false,
              "link": {
                "url": "",
                "method": "",
                "headers": [
                  {
                    "key": "",
                    "value": ""
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
        "url": "https://animepahe.com/api?m=search&l=8&q=<searched>",
        "method": "get",
        "headers": [
          {
            "key": "",
            "value": ""
          }
        ],
        "httpBody": null
      },
      "separator": "%20",
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
        "javaScript": "const DefaultLayouts = {ultraWideFull: 'ultraWideFull', ultraWide: 'ultraWide', wideFull: 'wideFull', wide: 'wide', wideStrechedFull: 'wideStrechedFull', wideStrechedFullDouble: 'WideStrechedFullDouble', wideStreched: 'wideStreched', wideStrechedDouble: 'wideStrechedDouble', wideStrechedFullList: 'wideStrechedFullList', wideStrechedList: 'wideStrechedList', doublets: 'doublets', doubletsDouble: 'doubletsDouble', doubletsFull: 'doubletsFull', doubletsFullDouble: 'doubletsFullDouble', doubletsConstant: 'doubletsConstant', doubletsDoubleConstant: 'doubletsDoubleConstant', doubletsFullConstant: 'doubletsFullConstant', doubletsFullDoubleConstant: 'doubletsFullDoubleConstant', longDoublets: 'longDoublets', longDoubletsDouble: 'longDoubletsDouble', longDoubletsFull: 'longDoubletsFull', longDoubletsFullDouble: 'longDoubletsFullDouble', longDoubletsConstant: 'longDoubletsConstant', longDoubletsDoubleConstant: 'longDoubletsDoubleConstant', longDoubletsFullConstant: 'longDoubletsFullConstant', longDoubletsFullDoubleConstant: 'longDoubletsFullDoubleConstant', triplets: 'triplets', tripletsDouble: 'tripletsDouble', tripletsFull: 'tripletsFull', tripletsFullDouble: 'tripletsFullDouble', tripletsConstant: 'tripletsConstant', tripletsDoubleConstant: 'tripletsDoubleConstant', tripletsFullConstant: 'tripletsFullConstant', tripletsFullDoubleConstant: 'tripletsFullDoubleConstant', longTriplets: 'longTriplets', longTripletsDouble: 'longTripletsDouble', longTripletsFull: 'longTripletsFull', longTripletsFullDouble: 'longTripletsFullDouble', longTripletsConstant: 'longTripletsConstant', longTripletsDoubleConstant: 'longTripletsDoubleConstant', longTripletsFullConstant: 'longTripletsFullConstant', longTripletsFullDoubleConstant: 'longTripletsFullDoubleConstant', none: ''};const CellDesings = { Special1: 'Special1', Special2: 'Special2', Special3: 'Special3', CELLHelperText: 'CELLHelperText', small1: 'small1', small2: 'small2', normal1: 'normal1', normal2: 'normal2', normal3: 'normal3', normal4: 'normal4', normal5: 'normal5', normal6: 'normal6', normal7: 'normal7', wide1: 'wide1', wide2: 'wide2', wide3: 'wide3', wide4: 'wide4', wide5: 'wide5', wide6: 'wide6', wide7: 'wide7', wide8: 'wide8', wide9: 'wide9', wide10: 'wide10', wide11: 'wide11'};const Paging = { leading: 'leading', centered: 'centered', none: ''};const Orientation = { horizontal: 'horizontal', vertical: 'vertical'};function Search(request, extra, separator, javascriptConfig, output) { this.request = request; this.extra = extra; this.separator = separator; this.javascriptConfig = javascriptConfig; this.output = output;}function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody;}function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo;}function Commands(commandName, params) { this.commandName = commandName; this.params = params;}function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript;}function KeyValue(key, value) { this.key = key; this.value = value;}function Output(cellDesing, orientation, defaultLayout, paging, section, layout, data) { this.cellDesing = cellDesing; this.orientation = orientation; this.defaultLayout = defaultLayout; this.paging = paging; this.section = section; this.layout = layout; this.data = data;}function Section(sectionName, separator) { this.sectionName = sectionName; this.separator = separator;}function Layout(insets, visibleCellsWidthS, visibleCellsWidthM, visibleCellsWidthL, visibleCellsHeight, heightForVisibleCells, cellSize, ratio, constant, horizontalSpacing, verticalSpacing) { this.insets = insets; this.visibleCellsWidthS = visibleCellsWidthS; this.visibleCellsWidthM = visibleCellsWidthM; this.visibleCellsWidthL = visibleCellsWidthL; this.visibleCellsHeight = visibleCellsHeight; this.heightForVisibleCells = heightForVisibleCells; this.cellSize = cellSize; this.ratio = ratio; this.constant = constant; this.horizontalSpacing = horizontalSpacing; this.verticalSpacing = verticalSpacing;}function Insets(top, bottom, left, right) { this.top = top; this.bottom = bottom; this.left = left; this.right = right;}function Size(width, height) { this.width = width; this.height = height;}function Ratio(inRelation, number1, number2) { this.inRelation = inRelation; this.number1 = number1; this.number2 = number2;}function Data(image, title, description, field1, field2, field3, field4, isChapter, link, openInWebView) { this.image = image; this.title = title; this.description = description; this.field1 = field1; this.field2 = field2; this.field3 = field3; this.field4 = field4; this.isChapter = isChapter; this.link = link; this.openInWebView = openInWebView;}function quickData(link, image, title, field1) { return new Data(image, title, 'unknown', field1, 'unknown', 'unknown', 'unknown', false, link);}function shuffle(a) { var j, x, i; for (i = a.length - 1; i > 0; i--) { j = Math.floor(Math.random() * (i + 1)); x = a[i]; a[i] = a[j]; a[j] = x; } return a;}var savedData = document.getElementById('ketsu-final-data');var parsedJson = JSON.parse(savedData.innerHTML);let output = [];let emptyKeyValue = [new KeyValue('', '')];var data = JSON.parse(document.querySelector('script').innerText.replace('/*', '').replace('*/', '')).data;let results = [];for (var x = 0; x < data.length; x++) { let image = data[x].poster; let link = 'https://pahe.win/a/' + data[x].id + '?id=' + data[x].id; image = new ModuleRequest(image, 'get', emptyKeyValue, null); link = new ModuleRequest(link, 'get', emptyKeyValue, null); let title = data[x].title; let type = data[x].type; let year = data[x].year.toString(); let status = data[x].status; let season = data[x].season; let score = data[x].score.toString(); results.push(new Data(image, title, status, type, year, season, score + '/10', false, link));}let horizontalLayout = new Layout(new Insets(10, 10, 10, 10), 1, 2, 3, 1, 500, new Size(400, 400), new Ratio('width', 4, 11), new Size(0, 0), 10, 10);output.push(new Output(CellDesings.wide11, Orientation.vertical, DefaultLayouts.none, Paging.none, new Section('', false), horizontalLayout, results));let searchPageObject = new Search(new ModuleRequest('', '', emptyKeyValue, null), new Extra([new Commands('', emptyKeyValue)], emptyKeyValue), '', new JavascriptConfig(true, false, ''), output);var finalJson = JSON.stringify(searchPageObject);savedData.innerHTML = finalJson;"
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
                "url": "",
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
              "openInWebView" : false,
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
        "url": "",
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
        "javaScript": "function Info(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output;}function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody;}function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo;}function Commands(commandName, params) { this.commandName = commandName; this.params = params;}function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript;}function KeyValue(key, value) { this.key = key; this.value = value;}function Chapter(chapName, link,openInWebView) { this.chapName = chapName; this.link = link; this.openInWebView = openInWebView;}function Output(image, title, link, description, genres, field1, field2, field3, field4, chapters) { this.image = image; this.link = link; this.title = title; this.description = description; this.genres = genres; this.field1 = field1; this.field2 = field2; this.field3 = field3; this.field4 = field4; this.chapters = chapters;}function getStuff(array,match) { for (var x = 0 ; x< array.length;x++) { let data = array[x].innerText; if (data.includes(match)) { return data.replace(match,'').trim(); } } }function getHtmlStuff(array,match) { for (var x = 0 ; x< array.length;x++) { let data = array[x].innerText; if (data.includes(match)) { return array[x]; } }}var savedData = document.getElementById('ketsu-final-data');var parsedJson = JSON.parse(savedData.innerHTML);let emptyKeyValue = [new KeyValue('', '')];var episodes = [];var type = '';var status = '';var genres = [];var desc = '';var title = document.querySelector('.title-wrapper > h1').innerText;var image = document.querySelector('.anime-poster > a > img').getAttribute('src');image = new ModuleRequest(image,'get',emptyKeyValue,null);var genresArray = [];var season = '';var eplength = '';desc = document.querySelector('.anime-synopsis').innerText;var data = document.querySelector('.anime-info').querySelectorAll('p');data.forEach(function(element) { var text = element.innerText; if (text.includes('Status:')) { status = text.replace('Status: ', ''); } console.log(text); if (text.includes('Type:')) { type = text.replace('Type: ', ''); } if (text.includes('Season: ')) { season = text.replace('Season: ',''); } if (text.includes('Episodes: ')) { eplength = text.replace('Episodes: ',''); }});genresArray = document.querySelector('.anime-genre').querySelectorAll('li');if (genresArray.length < 1) { genres = [''];}genresArray.forEach(function(element) { genres.push(element.innerText);});var id = parsedJson.request.url.split('?id=')[1];let infoPageObject = new Info(new ModuleRequest('https://animepahe.com/api?m=release&id=' + id + '&l=30&sort=episode_desc&page=1', 'get', emptyKeyValue, null), new Extra([new Commands('', emptyKeyValue)], emptyKeyValue), new JavascriptConfig(false, false, ''), new Output(image, title, parsedJson.request, desc, genres, status, season, type, 'Eps: ' + eplength, episodes));var finalJson = JSON.stringify(infoPageObject);savedData.innerHTML = finalJson;"
      },
      "output": {
        "image": {
          "url": "",
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
          "url": "",
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
    },{
      "request": {
        "url": "",
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
        "javaScript": "function Info(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output;}function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody;}function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo;}function Commands(commandName, params) { this.commandName = commandName; this.params = params;}function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript;}function KeyValue(key, value) { this.key = key; this.value = value;}function Chapter(chapName, link, openInWebView) { this.chapName = chapName; this.link = link; this.openInWebView = openInWebView;}function Output(image, title, link, description, genres, field1, field2, field3, field4, chapters) { this.image = image; this.link = link; this.title = title; this.description = description; this.genres = genres; this.field1 = field1; this.field2 = field2; this.field3 = field3; this.field4 = field4; this.chapters = chapters;}function getStuff(array, match) { for (var x = 0; x < array.length; x++) { let data = array[x].innerText; if (data.includes(match)) { return data.replace(match, '').trim(); } }}function getHtmlStuff(array, match) { for (var x = 0; x < array.length; x++) { let data = array[x].innerText; if (data.includes(match)) { return array[x]; } }}var savedData = document.getElementById('ketsu-final-data');var parsedJson = JSON.parse(savedData.innerHTML);let emptyKeyValue = [new KeyValue('', '')];var episodes = [];var data = JSON.parse(document.querySelector('script').innerText.replace('/*', '').replace('*/', ''));var total = data.total;var perPage = data.per_page;var request = parsedJson.request;for (var x = 1; x <= total; x++) { var page = Math.floor(x / perPage) + 1; var episode = x % perPage - 1; var link = parsedJson.request.url.split('page=')[0] + 'page=' + page + '&ep=' + episode; link = new ModuleRequest(link, 'get', emptyKeyValue, null); episodes.push(new Chapter('', link, false));}episodes = episodes.reverse();for (var x = 0; x < episodes.length; x++) { let episode = x + 1; episodes[x].chapName = 'Episode ' + episode;}var id = parsedJson.request.url.split('?id=')[1];let infoPageObject = new Info(new ModuleRequest('', 'get', emptyKeyValue, null), new Extra([new Commands('', emptyKeyValue)], emptyKeyValue), new JavascriptConfig(false, false, ''), new Output(parsedJson.output.image, parsedJson.output.title, parsedJson.output.link, parsedJson.output.description, parsedJson.output.genres, parsedJson.output.field1, parsedJson.output.field2, parsedJson.output.field3, parsedJson.output.field4, episodes));var finalJson = JSON.stringify(infoPageObject);savedData.innerHTML = finalJson;"
      },
      "output": {
        "image": {
          "url": "",
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
          "url": "",
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
        "url": "",
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
        "javaScript": "function Chapters(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output; } function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody; } function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo; } function Commands(commandName, params) { this.commandName = commandName; this.params = params; } function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript; } function KeyValue(key, value) { this.key = key; this.value = value; } function Output( videos, images, text) { this.videos = videos; this.images = images; this.text = text; } function Videos(needsResolver, rawVideo) { this.needsResolver = needsResolver; this.rawVideo = rawVideo; } function NeedsResolver(resolverIdentifier, link) { this.resolverIdentifier = resolverIdentifier; this.link = link; } function RawVideo(video) { this.video = video; } function Video(videoQuality, videoLink) { this.videoQuality = videoQuality; this.videoLink = videoLink; } function Text(text) { this.text = text; } var output = []; var savedData = document.getElementById('ketsu-final-data'); var parsedJson = JSON.parse(savedData.innerHTML); var emptyKeyValue = [new KeyValue('', '')]; var data = JSON.parse(document.querySelector('script').innerText.replace('/*', '').replace('*/', '')); var episode = parseInt(parsedJson.request.url.split('ep=')[1]); var selected = data.data[episode]; var episodeLink = 'https://animepahe.com/api?m=embed&id='+selected.anime_id+'&session='+selected.session+'&p=kwik'; let emptyExtra = new Extra([new Commands('', emptyKeyValue)], emptyKeyValue); var chaptersObject = new Chapters(new ModuleRequest(episodeLink, 'get', emptyKeyValue, null), emptyExtra, new JavascriptConfig(false, false, ''), new Output(new Videos(null, output), null, null)); var finalJson = JSON.stringify(chaptersObject); savedData.innerHTML = finalJson;"
      },
      "output": {
        "videos": {
          "needsResolver": [
            {
              "resolverIdentifier": "",
              "link": {
                "url": "",
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
                  "videoQuality": "",
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
    },{
      "request": {
        "url": "",
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
        "javaScript": "function Chapters(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output;}function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody;}function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo;}function Commands(commandName, params) { this.commandName = commandName; this.params = params;}function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript;}function KeyValue(key, value) { this.key = key; this.value = value;}function Output(videos, images, text) { this.videos = videos; this.images = images; this.text = text;}function Videos(needsResolver, rawVideo) { this.needsResolver = needsResolver; this.rawVideo = rawVideo;}function NeedsResolver(resolverIdentifier, link) { this.resolverIdentifier = resolverIdentifier; this.link = link;}function RawVideo(video) { this.video = video;}function Video(videoQuality, videoLink) { this.videoQuality = videoQuality; this.videoLink = videoLink;}function Text(text) { this.text = text;}var output = [];var savedData = document.getElementById('ketsu-final-data');var parsedJson = JSON.parse(savedData.innerHTML);var emptyKeyValue = [new KeyValue('', '')];var data = JSON.parse(document.querySelector('script').innerText.replace('/*', '').replace('*/', '')).data;let keyValue = [new KeyValue('Referer', 'https://animepahe.com')];for (var x = 0; x < data.length; x++) { for (var i = 0; i < 1081; i++) { var serverjson = data[x][i]; if (serverjson !== undefined) { if (i == 360 || i == 480 || i == 720 || i == 800 || i == 1080) { let servername = 'KWIK-' + i + 'p' + '-' + serverjson.audio; output.push(new NeedsResolver(servername.toUpperCase(), new ModuleRequest(serverjson.kwik, 'get', keyValue, null))); } else { let servername = 'KWIK-' + serverjson.audio; output.push(new NeedsResolver(servername.toUpperCase(), new ModuleRequest(serverjson.kwik, 'get', keyValue, null))); } } }}output = output.reverse();let emptyExtra = new Extra([new Commands('', emptyKeyValue)], emptyKeyValue);var chaptersObject = new Chapters(new ModuleRequest('', '', emptyKeyValue, null), emptyExtra, new JavascriptConfig(false, false, ''), new Output(new Videos(output, null), null, null));var finalJson = JSON.stringify(chaptersObject);savedData.innerHTML = finalJson;"
      },
      "output": {
        "videos": {
          "needsResolver": [
            {
              "resolverIdentifier": "",
              "link": {
                "url": "",
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
                  "videoQuality": "",
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
        "resolverName": "KWIK",
        "nameMatches": [
          "KWIK","KWIK-JPN","KWIK-ENG","KWIK-360P-JPN","KWIK-480P-JPN","KWIK-720P-JPN","KWIK-800P-JPN","KWIK-1080P-JPN","KWIK-360P-ENG","KWIK-480P-ENG","KWIK-720P-ENG","KWIK-800P-ENG","KWIK-1080P-ENG"
        ],
        "developer": "Noah G",
        "moduleID": "526746914151",
        "resolverVersion": 1,
        "baseURL": "https://kwik.cx/"
      },
      "resolver": [
        {
          "request": {
            "url": "",
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
            "javaScript": " function Resolver(request, extra, javascriptConfig, output) { this.request = request; this.extra = extra; this.javascriptConfig = javascriptConfig; this.output = output;}function ModuleRequest(url, method, headers, httpBody) { this.url = url; this.method = method; this.headers = headers; this.httpBody = httpBody;}function Extra(commands, extraInfo) { this.commands = commands; this.extraInfo = extraInfo;}function Commands(commandName, params) { this.commandName = commandName; this.params = params;}function JavascriptConfig(removeJavascript, loadInWebView, javaScript) { this.removeJavascript = removeJavascript; this.loadInWebView = loadInWebView; this.javaScript = javaScript;}function KeyValue(key, value) { this.key = key; this.value = value;}function Output(video) { this.video = video;}function Video(videoQuality, videoLink) { this.videoQuality = videoQuality; this.videoLink = videoLink;}function getNext(match, array) { for (var x = 0; x < array.length; x++) { let mMatch = array[x]; if (mMatch.includes(match)) { return array[x + 1]; } }}var savedData = document.getElementById('ketsu-final-data');var parsedJson = JSON.parse(savedData.innerHTML);var emptyKeyValue = [new KeyValue('', '')];var videos = [];let KeyValue1 = [new KeyValue('Referer', 'https://kwik.cx/'), new KeyValue('Accept', '*/*')];var ps = document.querySelectorAll('script');function getData(name, array) { for (var x = 0; x < array.length; x++) { var text = array[x]; if (text == name) { return array[x + 1]; } }}function getBeforeData(name, array) { for (var x = 0; x < array.length; x++) { var text = array[x]; if (text == name) { return array[x - 1]; } }}for (var x = 0; x < ps.length; x++) { var text = ps[x].innerHTML; if (text.includes('maxBufferLength') && !text.includes('bruhmoment')) { var data = text.split('|'); var id = ''; var longId = getBeforeData('storage', data); var uwu = ''; var maxLength = 'a'; for (var z = 0; z < data.length; z++) { var actualKey = data[z]; try { if (actualKey.includes('000')) { id = actualKey; } if (actualKey.length > maxLength.length && !actualKey.includes('(')) { maxLength = actualKey; } if (actualKey == 'uwu') { uwu = 'uwu.m3u8'; } if (actualKey == 'mon') { uwu = 'mon.key'; } } catch {} } longId = maxLength; var stream = 'stream'; var au = getData('nextstream', data); var eu = getData(au, data); var nextstream = 'nextstream'; var files = getData(eu, data); var finalLink = 'https://' + files + '-' + eu + '-' + au + '.' + nextstream + '.org/' + stream + '/' + id + '/' + longId + '/' + uwu; videos.push(new Video('Default', new ModuleRequest(finalLink, 'get', KeyValue1, null))); }}videos = videos.slice(0, 1);let emptyExtra = new Extra([new Commands('', emptyKeyValue)], emptyKeyValue);var chaptersObject = new Resolver(new ModuleRequest('', '', emptyKeyValue, null), emptyExtra, new JavascriptConfig(false, false, ''), new Output(videos));var finalJson = JSON.stringify(chaptersObject);savedData.innerHTML = finalJson;"
          },
          "output": {
            "moduleID": "",
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
