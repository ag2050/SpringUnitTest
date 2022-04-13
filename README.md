## Spring Boot Unit Testing

# @WebMvcTest
It applies configurations only relevent to MVC tests (i.e. @Controller, @ControllerAdvice, @JsonComponent, Converter/GenericConverter, Filter, WebMvcConfigurer and HandlerMethodArgumentResolver beans but not @Component, @Service or @Repository beans)
When using JUnit 4, this annotation should be used in combination with @RunWith(SpringRunner.class).

# @RunWith(SpringRunner.class)
This annotation integrates Junit 4 libraries with spring TestContext Framework. With SpringRunner , we can implement standard JUnit 4-based unit and integration tests.


