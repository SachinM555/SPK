package spkm;

import java.util.concurrent.TimeUnit;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.firefox.FirefoxDriver;
import org.testng.annotations.Test;

public class SPK {
 
  public WebDriver driver;
 
  @Test
  public void main() {
	  
      driver = new FirefoxDriver();
      driver.manage().timeouts().implicitlyWait(10, TimeUnit.SECONDS);
      driver.get("http://www.google.co.in");
      System.out.println("SPK");
      
      driver.manage().window().maximize();
      driver.quit();
      
  }
}