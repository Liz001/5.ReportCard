package com.example.android.reportcard;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;

// Italian Report Card


public class ReportCard {

    //School year (i.e. First class, Second class...)
    private String mYear;

    // Student name
    private String mStudent;

    // Subjects Grades, in Italy the grades range are from 1 to 10, 10 is the excellence, 1 is the worst
    private int mItalianGrade;
    private int mMathGrade;
    private int mScienceGrade;
    private int mEnglishGrade;
    private int mHistoryGrade;



    public ReportCard (String year, String student, int italianGrade, int mathGrade, int scienceGrade, int englishGrade, int historyGrade) {

        mYear = year;
        mStudent = student;
        mItalianGrade = italianGrade;
        mMathGrade = mathGrade;
        mScienceGrade = scienceGrade;
        mEnglishGrade = englishGrade;
        mHistoryGrade = historyGrade;
    }

    public String getmYear(){
        return mYear;
    }

    public void setmYear(String year){
        mYear = year;
    }

    public String getmStudent(){
        return mStudent;
    }

    public void setmStudent(String student){
        mStudent = student;
    }

    public int getmItalianGrade() {
        return mItalianGrade;
    }

    public void setmItalianGrade(int italianGrade) {
        mItalianGrade = italianGrade;
    }

    public int getmMathGrade() {
        return mMathGrade;
    }

    public void setmMathGrade(int mathGrade) {
        mMathGrade = mathGrade;
    }

    public int getmScienceGrade() {
        return mScienceGrade;
    }

    public void setmScienceGrade(int scienceGrade) {
        mScienceGrade = scienceGrade;
    }

    public int getmEnglishGrade() {
        return mEnglishGrade;
    }

    public void setmEnglishGrade(int englishGrade) {
        mEnglishGrade = englishGrade;
    }

    public int getmHistoryGrade() {
        return mHistoryGrade;
    }

    public void setmHistoryGrade(int historyGrade) {
        mHistoryGrade = historyGrade;
    }



    @Override
    public String toString(){
        return "School year: " + getmYear() +
                "\nName: " + getmStudent() +
                "\nItalian: " + getmItalianGrade() +
                "\nMath: " + getmMathGrade() +
                "\nScience: " + getmScienceGrade() +
                "\nEnglish: " + getmEnglishGrade() +
                "\nHistory: " + getmHistoryGrade();
    }
}