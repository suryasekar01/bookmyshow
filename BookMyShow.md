# bookmyshow
\\This is the code for our book my show testing.

package bookmy;
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class my {
	public static void main(String[] args)
	{
		System.getProperty("webdriver.chrome.driver","C:\\Users\\Surya\\Downloads\\chromedriver-win64\\chromedriver-win64\\chromedriver.exe");
		WebDriver web= new ChromeDriver();
		web.get("https://in.bookmyshow.com/");
		web.manage().window().maximize();
		web.findElement(By.xpath("//*[@id=\"modal-root\"]/div/div/div/div[1]/div/div/input"));
		web.findElement(By.xpath("//*[@id=\"modal-root\"]/div/div/div/div[1]/div/div/input"));
		web.findElement(By.xpath("//*[@id=\"modal-root\"]/div/div/div/div[4]/span")).click();
		web.findElement(By.xpath("//*[@id=\"modal-root\"]/div/div/div/div[4]/ul/li[266]/div")).click();
		web.findElement(By.xpath("//*[@id=\"super-container\"]/div[2]/div[1]/header/div[2]/div/div/div/div[1]/div/a[1]")).click();
		web.findElement(By.xpath("//*[@id=\"super-container\"]/div[2]/div[1]/header/div[1]/div/div/div/div[2]/div[2]/div[1]")).click();
	}

}




