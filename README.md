# major-google-dorks
Here are some major Google dorks commonly used in bug bounty hunting to discover potential vulnerabilities or exposed information:

"site:target.com" - This dork restricts the search to a specific target website, allowing you to find sensitive information or vulnerabilities within that domain.

"intitle:index.of" - This dork helps in finding directory listings or open directories that may expose sensitive files or directories.

"filetype:pdf" - This dork narrows down the search to PDF files, which sometimes contain sensitive information or configuration details that can be leveraged for attacks.

"inurl:/admin" - This dork searches for URLs that include the "/admin" path, which may lead to administration panels or login pages that could be misconfigured or vulnerable.

"filetype:php intext:SQL" - This dork focuses on PHP files that contain the term "SQL" within their contents, helping to identify potential SQL injection vulnerabilities.

"site:target.com ext:conf OR ext:txt OR ext:ini" - This dork searches for configuration files (such as .conf, .txt, or .ini files) on the target website, which may contain sensitive credentials or configuration details.

"inurl:login.php" - This dork looks for login pages on the target website, which can be a potential entry point for authentication-related vulnerabilities.

"site:target.com intext:apikey" - This dork helps identify instances where API keys or access tokens might have been exposed or disclosed within the target website.

"site:target.com intitle:error OR intitle:warning" - This dork searches for error or warning messages in the titles of web pages, which may reveal potential misconfigurations or error-based vulnerabilities.

"site:target.com intext:"Vulnerable to XSS"" - This dork helps identify web pages that contain specific text indicating they are vulnerable to cross-site scripting (XSS) attacks.

"site:target.com intext:username" - This dork searches for web pages that contain the term "username," which may reveal potential user-related vulnerabilities or exposed usernames.

"filetype:log site:target.com" - This dork targets log files on the target website, which can contain valuable information for identifying security issues or misconfigurations.

"site:target.com ext:sql" - This dork focuses on SQL files within the target website, which may contain database schemas, queries, or other sensitive information that could lead to SQL injection vulnerabilities.

"inurl:/cgi-bin/ site:target.com" - This dork searches for CGI scripts or executables on the target website, which may be prone to vulnerabilities like command injection or remote code execution.

"site:target.com intitle:admin OR intitle:dashboard" - This dork helps identify administrative pages or dashboards within the target website, which may have misconfigurations or weak access controls.

"site:target.com intext:password" - This dork looks for web pages containing the term "password," which may indicate potential password-related vulnerabilities or exposed passwords.

"filetype:sql inurl:/config/ site:target.com" - This dork targets SQL files within the "/config/" directory on the target website, which often store database connection details or sensitive configurations.

"site:target.com ext:php intitle:index of" - This dork searches for PHP files with an "index of" title, which may lead to directories containing PHP source code that could be analyzed for security vulnerabilities.

"inurl:/wp-content/uploads/ site:target.com" - This dork targets WordPress uploads directories, which may inadvertently expose sensitive files or provide insights into the underlying website structure.

"site:target.com intext:"Access Denied" OR intext:"Unauthorized"" - This dork searches for web pages displaying access denial or unauthorized messages, which could indicate potential access control issues or misconfigurations.

stay tuned many more to come.!!