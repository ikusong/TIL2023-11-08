# TIL2023-11-08
package test;

public class Student {
   private int math;
   private int eng;
   private int kor;
   private String grade;

   public Student(int math, int eng, int kor, String grade) {
      this.math = math;
      this.eng = eng;
      this.kor = kor;
      this.grade = grade;
   }

   int getTotal() {
      return this.eng + this.kor + this.math;
   }

   double getAvg() {
      return getTotal() / 3.0;
   }

   public int getMath() {
      return math;
   }

   public int getEng() {
      return eng;
   }

   public int getKor() {
      return kor;
   }

   public String getGrade() {
      return grade;
   }

