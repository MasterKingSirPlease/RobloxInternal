<b>
  
  NOTES
  
</b>

While HttpService can only be used on the server, this can be used on client too.

<hr>

<b>
  
  GetDocumentationUrl(partialUrl: string):string
  
</b>

Returns a string containing 'https://developer.roblox.com/partialUrl'


<b>

  GetAsync(apiUrlPath: string, priority: ThrottlingPriority, httpRequestType: HttpRequestType): string  YIELDS
  
</b>

"Performs a GET request on an official Roblox web API."
Returns a GetAsync on api.roblox.com/apiUrlPath. Little documentation on HttpRequestType at this time.


<b>
  
  GetAsyncFullUrl(apiUrl: string, priority: ThrottlingPriority, httpRequestType: HttpRequestType): string  YIELDS
  
</b>

Basically a GetAsync from normal HttpService but it only allows roblox.com
If not a roblox.com endpoint then errors with "Non-trusted BaseURL used. HttpRbxApiService is only for Roblox API calls."


<b>
  PostAsync(apiUrlPath: string, data: string, priority: ThrottlingPriority, content_type: HttpContentType, httpRequestType: HttpRequestType): string  YIELDS
</b>

"Performs a POST request to the specified Roblox Web API The apiUrlPath parameter is prefixed by https://api.roblox.com/ when the post request is made."
Returns a PostAsync on api.roblox.com/apiUrlPath.


<b>
  PostAsyncFullUrl(apiUrl: string, data: string, priority: ThrottlingPriority, content_type: HttpContentType, httpRequestType: HttpRequestType): string  YIELDS
</b>

Basically a PostAsync from normal HttpService but it only allows roblox.com
If not a roblox.com endpoint then errors with "Non-trusted BaseURL used. HttpRbxApiService is only for Roblox API calls."


<b>
  RequestAsync(requestOptions: table, priority: ThrottlingPriority, content_type: HttpContentType, httpRequestType: HttpRequestType): string  YIELDS
</b>

Basically a RequestAsync from normal HttpService but it only allows roblox.com
If not a roblox.com endpoint then errors with "Non-trusted BaseURL used. HttpRbxApiService is only for Roblox API calls."


<b>
  RequestLimitedAsync(requestOptions: table, priority: ThrottlingPriority, content_type: HttpContentType, httpRequestType: HttpRequestType): string  YIELDS
</b>

Nobody knows what it's for. Returns "ReqestLimitedAsync is disabled (error=1)"
