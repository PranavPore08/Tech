import org.openqa.selenium.chrome.ChromeDriver;

public class Temp_class {
	public static void main(String[] args) {
		System.setProperty("webdriver.chrome.driver", "C:\\browserdrivers\\chromedriver.exe");
		
		ChromeDriver driver=new ChromeDriver();
		driver.get("https://www.google.com");
	}
}
