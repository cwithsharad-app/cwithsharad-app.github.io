---
layout: post
title: "Program for traversing and displaying a matrix"
author: Priyansh Srivastava
date: 2018-12-31 23:11:00 Z
categories:
- DATA STRUCTURES
- C LANGUAGE PROGRAMS
- BASIC PROGRAMS
- ARRAY PROGRAMS
---

**PROGRAM CODE**

```c
#include<iostream.h>
#include<conio.h>

void main()
{
clrscr();
int arr[10][10],n,m,i,j;
cout<<"Enter the number of rows: ";
cin>>m;
cout<<"Enter the number of columns: ";
cin>>n;
cout<<"\nEnter "<<m*n<<" values for the Matrix:\n\n";
for(i=0;i<m;i++)
{
for(j=0;j<n;j++)
{
cin>>arr[i][j];
}
}
cout<<"\nTraversing and Displaying the Given Matrix:\n\n";
for(i=0;i<m;i++)
{
for(j=0;j<n;j++)
{
cout<<"\t"<<arr[i][j];
}
cout<<"\n";
}
getch();
}
```

**OUTPUT**

![{{post.title}}]({{site.baseurl}}/assets/post_images/ds1.jpg)
