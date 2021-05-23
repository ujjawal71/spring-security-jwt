# spring-security-jwt

All spring-boot-annotations

<ul class="points">
<li><strong>@GetMapping:</strong> It maps the <strong>HTTP GET</strong> requests on the specific handler method. It is used to create a web service endpoint that <strong>fetches</strong> It is used instead of using: <strong>@RequestMapping(method = RequestMethod.GET)</strong></li>
<li><strong>@PostMapping:</strong> It maps the <strong>HTTP POST </strong>requests on the specific handler method. It is used to create a web service endpoint that <strong>creates</strong> It is used instead of using: <strong>@RequestMapping(method = RequestMethod.POST)</strong></li>
<li><strong>@PutMapping:</strong> It maps the <strong>HTTP PUT</strong> requests on the specific handler method. It is used to create a web service endpoint that <strong>creates</strong> or <strong>updates</strong> It is used instead of using: <strong>@RequestMapping(method = RequestMethod.PUT)</strong></li>
<li><strong>@DeleteMapping:</strong> It maps the <strong>HTTP DELETE</strong> requests on the specific handler method. It is used to create a web service endpoint that <strong>deletes </strong>a resource. It is used instead of using: <strong>@RequestMapping(method = RequestMethod.DELETE)</strong></li>
<li><strong>@PatchMapping:</strong> It maps the <strong>HTTP PATCH </strong>requests on the specific handler method. It is used instead of using: <strong>@RequestMapping(method = RequestMethod.PATCH)</strong></li>
<li><strong>@RequestBody:</strong> It is used to <strong>bind</strong> HTTP request with an object in a method parameter. Internally it uses <strong>HTTP MessageConverters</strong> to convert the body of the request. When we annotate a method parameter with <strong>@RequestBody,</strong> the Spring framework binds the incoming HTTP request body to that parameter.</li>
<li><strong>@ResponseBody:</strong> It binds the method return value to the response body. It tells the Spring Boot Framework to serialize a return an object into JSON and XML format.</li>
<li><strong>@PathVariable:</strong> It is used to extract the values from the URI. It is most suitable for the RESTful web service, where the URL contains a path variable.&nbsp;We can define multiple @PathVariable in a method.</li>
<li><strong>@RequestParam:</strong> It is used to extract the query parameters form the URL. It is also known as a <strong>query parameter</strong>. It is most suitable for web applications. It can specify default values if the query parameter is not present in the URL.</li>
<li><strong>@RequestHeader:</strong> It is used to get the details about the HTTP request headers. We use this annotation as a <strong>method parameter</strong>. The optional elements of the annotation are <strong>name, required, value, defaultValue. </strong>For each detail in the header, we should specify separate annotations. We can use it multiple time in a method</li>
<li><strong>@RestController:</strong> It can be considered as a combination of <strong>@Controller</strong> and <strong>@ResponseBody </strong>annotations<strong>.</strong> The @RestController annotation is itself annotated with the @ResponseBody annotation. It eliminates the need for annotating each method with @ResponseBody.</li>
<li><strong>@RequestAttribute:</strong> It binds a method parameter to request attribute. It provides convenient access to the request attributes from a controller method. With the help of @RequestAttribute annotation, we can access objects that are populated on the server-side.</li>
</ul>
