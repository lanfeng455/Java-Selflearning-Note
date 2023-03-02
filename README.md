# Java-Selflearning-Note
封装(Encapsulation)
为了避免用户任意更改数据细节，我们将数据细节隐藏起来，仅公开有限的接口来交换数据内容。上述的方法称为“封装”。
下面是封装的实例：
public class GPA{
  private int totalScore;
  public int getScore(){
    return totalScore;
    }
  
  public void setScore(int totalScore){
    if(totalScore < 0 || totalScore > 100){
      System.out.println("Error!");
      return;
      }
      this.totalScore = totalScore;
      }
    }
  }
