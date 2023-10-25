@RestController
public class HelloController {
    @GetMapping("/")
    public String sayHello() {
        return "Hello, Git!";
    }
}
