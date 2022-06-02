<div align="center">
<a href="https://www.facehom.com/" target="_self">
<img src="https://github.com/JowoScript/JowoScript_Technology/blob/core/icon.png" 
     title="*JowoScript Technology and *JowoStyle Technology"
     alt="*JowoScript Technology and *JowoStyle Technology"     
     height="150px" width="150px"></img>
</a>
</div>
<div align="center">
<strong>
	*jS Technology
</strong>
<br>
<strong>
	*JowoScript Technology and *JowoStyle Technology
</strong>
<br>
<strong>
	Introduction
</strong>
</div>
<br><br>
<div align="center">
<strong>
	*JowoScript Technology is undefined technology, typing less, compiler language, complex structure, small size and faster (build with 💓🦄)
</strong>
</div>
<br>
<div align="center">	
<strong>
	*JowoStyle Technology is undefined technology for a pattern core of computation style language used for describing the presentation of *JowoScript Technology (build with 💓🦄)
</strong>
</div>
<br><br>

<details>
<summary>Support Technology :</summary>
<strong>	
<ul><li><bold>*JowoScript Technology build with bytecode concept with methode Just In Time (JIT) and writing in notepad.</bold></li><li><bold>*JowoStyle Technology build with core of computation style concept with methode Just In Time (JIT) and writing in notepad.</bold></li><li>Auto compiler file extension *.jowo</li><li>Auto compiler file extension *.jawa</li><li>Auto compiler file extension *.js3</li><li>Auto compiler file extension *.jss</li><li>Support TypeScript above version 1.0.0 auto compiler file *.ts (the mean is a good combination for each other to make enterprise systems or other like Ai, ML, AR, VR, etc in the future) I call this the Checkmate</li><li>Dive Deeper JowoStyle Runtimes of compiler type, condition, utility inside file extension *.jss or *.js3 and application/jowostyle</li><li>Dive Deeper JowoScript Runtimes of compiler type, condition, utility inside file extension *.jowo and application/jowoscript</li><li>Encryption end to end (Meaning i.e is that all data linked to jowoscript will be automatically encrypted with source code base)</li><li>JowoScript Technology cannot be detected by third-party technology or the like because the source code of JowoScript Technology is end-to-end encryption, meaning that it is not easily read by bad hackers or cybercriminals.</li><li>Very easy to install on multiplatform servers to deploy because it is a cross platform with javascript technology standard</li><li>Responsive mode user interface (Meaning i.e. when your design is in tablet mode, mobile or phone mode, television mode, LCD(Liquid Crystal Display) mode and laptop mode)</li><li>Cross platform (For example, a cross-platform application may run on Microsoft Mobile, Microsoft Windows, Android, z/OS, Linux OS, Unix OS, iOS and macOS)</li><li>Smart automatic detection error in javascript engine</li><li>Smart automatic detection error in jowoscript engine</li><li>Smart automatic jowoscript in Java Enterprise Edition (JEE)</li><li>Handling array of objects and decided multiple of attributes and pseudo</li><li>Licensed under privilege of creator technology (How to get token license contact email cohayfun@gmail)</li></ul>
</strong>
</details>

```html
/*
 * @jowo.version        : xx.xx.xx (JSRevamp Mission).
 * @jowo.owner        	: Muhammad Nurcahyo Pratomo
 * @jowo.creator	: Muhammad Nurcahyo Pratomo
 * @jowo.architect	: Muhammad Nurcahyo Pratomo
 * @jowo.author         : Muhammad Nurcahyo Pratomo
 * @jowo.founder        : Muhammad Nurcahyo Pratomo 
 * @jowo.developer	: Muhammad Nurcahyo Pratomo 
 * @jowo.license        : Licensed under privilege of creator technology (How to get token license contact email cohayfun@gmail).
 * @jowo.technology     : *JowoScript Technology and *JowoStyle Technology
 * @jowo.copyright      : Copyright 2021 - No Limited. *JowoScript Technology and *JowoStyle Technology. All rights reserved.
 */

Example :
mnp attribute		: mnp("mnp^object"), jowo("mnp^object"), mnp("^object"), jowo("^object");
jowo attribute		: mnp("jowo*object"), jowo("jowo*object"), mnp("*object"), jowo("*object");
jawa attribute		: mnp("jawa@object"), jowo("jawa@object"), mnp("@object"), jowo("@object");
id attribute		: mnp("id*object"), jowo("id*object"), mnp("id^object"), jowo("id^object"), mnp("id@object"), jowo("id@object"), mnp("#object"), jowo("#object");
class attribute		: mnp("class*object"), jowo("class*object"), mnp("class^object"), jowo("class^object"), mnp("class@object"), jowo("class@object"), mnp(".object"), jowo(".object");
name attribute		: mnp("name*object"), mnp("name^object"), mnp("name@object");
array of attribute 	: mnp("[ jowo*object, [jowo*object], element[attribute], node[node] ]")	mnp("element[attribute="value"], [attribute="value"], [attribute="value"] [attribute]");
array of pseudo		: mnp("[ element:pseudo, node:pseudo ], element:pseudo node:pseudo object:pseudo ");

More Information you can look example at:
https://www.facehom.com
```
<br>
<div align="center"><strong>Architecture of *JowoScript Technology and *JowoStyle Technology</strong></div>
<details>
<summary>Click to view image</summary>	
<img src="https://github.com/JowoScript/JowoScript_Technology/blob/core/architecture of jowoscript technology-version 0.2.1.png" title="Architecture of *JowoScript Technology and *JowoStyle Technology">
</details>
<br>
<div align="center"><strong>Installation information</strong></div>
<details>
<summary>Installation iOS - MacOS</summary>
	
```java
//Let's call class WKWebViewConfiguration(), WKWebView(frame, config), URL(url root) and URLRequest(base string url)
import UIKit
import WebKit
class ViewController: UIViewController, WKUIDelegate {
    var webView: WKWebView!
    override func loadView() {
        let webConfiguration = WKWebViewConfiguration()
        webView = WKWebView(frame: .zero, configuration: webConfiguration)
        webView.uiDelegate = self
        view = webView
    }
    override func viewDidLoad() {
        super.viewDidLoad()        
        let myURL = URL(string:"jowo-script.js")
        let myRequest = URLRequest(url: myURL!)
        webView.load(myRequest) //Load from url base webview class
	webView.loadHTMLString("<script>jowo.technology</script>", baseURL: myURL)
	//Result : JowoScript Technology
    }
}
```
iOS - MacOS, More information you can look at [here](https://developer.apple.com/documentation/webkit/wkwebview)
</details>
<details>
<summary>Installation server side Liferay Framework</summary>
	
```java
//Call this class JSTopHeadDynamicInclude extends BaseDynamicInclude (include, register)
@Component(immediate = true, service = DynamicInclude.class)
public class JSTopHeadDynamicInclude extends BaseDynamicInclude {
	@Override
	public void include(HttpServletRequest request, HttpServletResponse response, String key)
		throws IOException {
		PrintWriter printWriter = response.getWriter();
		String content = "<script href=\"http://localhost:8080/../../js/jowo-script.js\" type = \"text/javascript\" />";
		String jowoScript = "jowo.technology" type = \"text/javascript\" />";
		printWriter.println(jowoScript);
		//In console IDE like eclipse, rational application developer, jetbrains, netbeans, browser environment, etc. 
		//Result : JowoScript Technology
	}
	@Override
	public void register(DynamicIncludeRegistry dynamicIncludeRegistry) {
		dynamicIncludeRegistry.register("/html/common/themes/top_js.jspf#resources");		
	}  
}
```
Liferay Framework, More information you can look at [here](https://help.liferay.com/hc/en-us/articles/360018165751-Top-JS-Dynamic-Include-)
</details>
<details>
<summary>Installation Zkoss Framework</summary>
	
```javascript
<zk>
<script type="text/javascript" src="jowo-script.js"></script>
<window title="sample jowo script" border="none" width="100%" closable="true">	
	<script type="text/javascript">
		jowo.technology
	</script>
	//Result : JowoScript Technology
</window>
</zk>
```
</details>
<details>
<summary>Installation Android</summary>
	
```java
webview.loadDataWithBaseURL("file:///android_asset/javascript/jowo-script.js", page, "text/javascript", null, null);
```
Android, More information you can look at [here](https://developer.android.com/guide/webapps/webview#kotlin)
</details>
<details>
<summary>Installation Microsoft DOT NET</summary>

```cs
/* Let's call this function in server side */
/* 
@Function method call in server side
public string GetWebResourceUrl (Type type, string resourceName);
*/

using System;
using System.Web;
using System.Web.UI;
using System.Security.Permissions;
[assembly: WebResource("Samples.AspNet.CS.Controls.jowo-script.js", "application/x-javascript")]
namespace Samples.AspNet.CS.Controls
{
    [AspNetHostingPermission(SecurityAction.Demand, Level = AspNetHostingPermissionLevel.Minimal)]
    public class ClientScriptResourceLabel
    {
		Console.WriteLine(jowo.technology);
		//Result : JowoScript Technology
    }
}
```
Microsoft DOT NET, More information you can look at [here](https://docs.microsoft.com/en-us/dotnet/api/system.web.ui.clientscriptmanager.getwebresourceurl?redirectedfrom=MSDN&view=netframework-4.8#System_Web_UI_ClientScriptManager_GetWebResourceUrl_System_Type_System_String_)
</details>
<details>
<summary>Installation standart HTML</summary>

<b>Make sure your code JavaScript tag install.</b>
	
```html
<html>
<head>
<script type="text/javascript" src="jowo-script.js"></script>
</head>
<body>
	<script type="text/jowoscript">
		<string> strong = 'JowoScript walking alone';
		<int> count = 1 / 9999;
		jowo.information( strong );
		jowo.information('Result :'+count);
		//Result JowoScript walking alone
		//Result 0.00010001000100010001
	</script>
	<jowo-script>
		jowo.information( jowo.technology );
		//Result JowoScript Technology
	</jowo-script>
</body>
</html>
```
</details>

#### Creator
```html
muhammad nurcahyo pratomo
```
#### Copyright
```html
*JowoScript Technology and *JowoStyle Technology
```
#### License
Licensed under privilege of creator technology
