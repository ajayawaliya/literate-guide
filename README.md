# literate-guide
@RestController
public class HomeController {

    @GetMapping("/")
    public String home() {
        return "Secure Hidden Service via Spring Boot";
    }
}
