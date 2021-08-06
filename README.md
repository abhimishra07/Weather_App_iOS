It shows location based weather screen, it fetches current gps location and sends data to open weather API and displays the current temperature and weather condition, Also integrated with a search bar in which you can search any particular city and it will show its weather condition.


## Fix for App Transport Security Override

```XML
	<key>NSAppTransportSecurity</key>
	<dict>
		<key>NSExceptionDomains</key>
		<dict>
			<key>openweathermap.org</key>
			<dict>
				<key>NSIncludesSubdomains</key>
				<true/>
				<key>NSTemporaryExceptionAllowsInsecureHTTPLoads</key>
				<true/>
			</dict>
		</dict>
	</dict>
```


Copyright © The App Brewery

