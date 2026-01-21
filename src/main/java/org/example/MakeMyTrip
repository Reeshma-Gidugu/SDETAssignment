import org.openqa.selenium.By; 
import org.openqa.selenium.WebDriver; 
import org.openqa.selenium.WebElement; 
import org.openqa.selenium.firefox.FirefoxDriver; 
  
public class MakeMyTrip { 
  
    public static void main(String[] args) { 
  
        System.setProperty("webdriver.gecko.driver", "geckodriver.exe"); 
        WebDriver driver = new FirefoxDriver(); 
        driver.get("https://www.makemytrip.com"); 
        driver.manage().window().maximize(); 
        WebElement mmtlogo = driver.findElement(By.xpath("//div[@id='header-container']/div[1]/a/img")); 
        System.out.println(mmtlogo.isDisplayed());  
        driver.quit(); 
    } 
} 
