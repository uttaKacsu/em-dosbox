
 
# Review of Computer Oriented Numerical Methods by R.S. Salaria
 
Numerical methods are techniques for solving mathematical problems using computers. They are widely used in science, engineering, and other fields that require numerical computations. Numerical methods can help find approximate solutions to problems that are too complex or impossible to solve analytically.
 
Computer Oriented Numerical Methods by R.S. Salaria is a book that provides a comprehensive coverage of the subject, with an emphasis on conceptual understanding and practical implementation. The book covers topics such as floating-point arithmetic, error analysis, interpolation, differentiation, integration, linear systems, eigenvalues, ordinary differential equations, partial differential equations, and optimization. The book also includes algorithms for various numerical methods, written in pseudo code and implemented in C, C++, and Fortran languages.
 
**DOWNLOAD ✓ [https://www.google.com/url?q=https%3A%2F%2Fimgfil.com%2F2uL8qE&sa=D&sntz=1&usg=AOvVaw08trlTu3VHWry47GTSoR4F](https://www.google.com/url?q=https%3A%2F%2Fimgfil.com%2F2uL8qE&sa=D&sntz=1&usg=AOvVaw08trlTu3VHWry47GTSoR4F)**


 
The book is suitable for undergraduate and postgraduate students of computer science, mathematics, physics, chemistry, and engineering. It can also be used as a reference book by researchers and professionals who need to apply numerical methods in their work. The book has several features that make it user-friendly and engaging, such as:
 
- Formulae for different numerical methods are derived in the simplest manner.
- Large number of programming exercises to test the understanding and skills acquired.
- Large number of multiple choice questions and review exercises to test the theoretical knowledge.
- Examples and illustrations to demonstrate the applications of numerical methods.
- Appendices that provide useful information such as mathematical tables, C/C++/Fortran syntax, and sample programs.

The book is available in PDF format online for free download[^2^]. The PDF file has 395 pages and a file size of 8.5 MB. The book can also be purchased from Khanna Publishing House[^1^] or other online platforms.
 
rs salaria computer oriented numerical methods pdf download,  computer oriented numerical methods by rs salaria ebook free,  computer oriented numerical methods rs salaria solutions manual,  computer oriented numerical methods by rs salaria khanna publishers,  rs salaria computer oriented numerical methods book review,  computer oriented numerical methods by rs salaria pdf 395 online,  computer oriented numerical methods rs salaria pdf google drive,  computer oriented numerical methods by rs salaria lecture notes,  computer oriented numerical methods rs salaria pdf 395 price,  computer oriented numerical methods by rs salaria syllabus,  rs salaria computer oriented numerical methods pdf 395 edition,  computer oriented numerical methods by rs salaria amazon,  computer oriented numerical methods rs salaria pdf flipkart,  computer oriented numerical methods by rs salaria pdf 395 sample,  rs salaria computer oriented numerical methods slideshare,  computer oriented numerical methods by rs salaria pdf 395 isbn,  computer oriented numerical methods rs salaria pdf 395 table of contents,  computer oriented numerical methods by rs salaria pdf 395 summary,  rs salaria computer oriented numerical methods pdf 395 errata,  computer oriented numerical methods by rs salaria pdf 395 quiz,  computer oriented numerical methods rs salaria pdf 395 exercises,  computer oriented numerical methods by rs salaria pdf 395 projects,  rs salaria computer oriented numerical methods pdf 395 code,  computer oriented numerical methods by rs salaria pdf 395 examples,  computer oriented numerical methods rs salaria pdf 395 algorithms,  computer oriented numerical methods by rs salaria pdf 395 topics,  rs salaria computer oriented numerical methods pdf 395 chapters,  computer oriented numerical methods by rs salaria pdf 395 references,  computer oriented numerical methods rs salaria pdf 395 bibliography,  computer oriented numerical methods by rs salaria pdf 395 appendix,  rs salaria computer oriented numerical methods pdf 395 glossary,  computer oriented numerical methods by rs salaria pdf 395 index,  computer oriented numerical methods rs salaria pdf 395 cover page,  computer oriented numerical methods by rs salaria pdf 395 preface,  rs salaria computer oriented numerical methods pdf 395 acknowledgements,  computer oriented numerical methods by rs salaria pdf 395 introduction,  computer oriented numerical methods rs salaria pdf 395 objectives,  computer oriented numerical methods by rs salaria pdf 395 outcomes,  rs salaria computer oriented numerical methods pdf 395 scope,  computer oriented numerical methods by rs salaria pdf 395 prerequisites,  computer oriented numerical methods rs salaria pdf 395 format,  computer oriented numerical methods by rs salaria pdf 395 features,  rs salaria computer oriented numerical methods pdf 395 benefits,  computer oriented numerical methods by rs salaria pdf 395 applications,  computer oriented numerical methods rs salaria pdf 395 limitations,  computer oriented numerical methods by rs salaria pdf 395 comparison,  rs salaria computer oriented numerical methods pdf 395 feedback,  computer oriented numerical methods by rs salaria pdf 395 testimonials,  computer oriented numerical methods rs salaria pdf 395 ratings,  computer oriented numerical methods by rs salaria pdf 395 reviews
  
In this article, we will review some of the main topics and concepts covered in the book Computer Oriented Numerical Methods by R.S. Salaria. We will also provide some examples and code snippets to illustrate how to implement the numerical methods using C, C++, and Fortran languages.
 
## Floating-Point Arithmetic
 
Floating-point arithmetic is a way of representing real numbers using a finite number of bits. It allows us to perform arithmetic operations on numbers that are very large or very small, with a reasonable accuracy. However, floating-point arithmetic also has some limitations and pitfalls, such as rounding errors, overflow, underflow, and loss of precision.
 
The book explains the basic concepts of floating-point arithmetic, such as the representation of floating-point numbers, the IEEE 754 standard, the machine epsilon, and the relative error. It also discusses some common sources of errors in floating-point arithmetic, such as cancellation, truncation, and accumulation. It provides some guidelines and techniques for avoiding or minimizing these errors, such as scaling, interval arithmetic, and error propagation analysis.
 
For example, consider the following C code snippet that computes the value of pi using the Leibniz formula:
 `
#include 
#include 

#define N 1000000 // number of terms

int main()

    double pi = 0.0; // approximate value of pi
    double sign = 1.0; // alternating sign
    double term; // current term
    int i; // loop counter

    for (i = 1; i <= 2 * N - 1; i += 2)
    
        term = sign / i; // compute the term
        pi += term; // add the term to the sum
        sign = -sign; // change the sign

    pi *= 4.0; // multiply by 4

    printf("The approximate value of pi is %.15f\n", pi);
    printf("The relative error is %.15f\n", fabs(pi - M_PI) / M_PI);

    return 0;

` 
The output of this program is:
 `
The approximate value of pi is 3.141591653589774
The relative error is 0.000000165480742
` 
This program uses a double type variable to store the approximate value of pi, which has a precision of about 15 decimal digits. However, if we use a float type variable instead, which has a precision of about 7 decimal digits, we get a different output:
 `
The approximate value of pi is 3.141593933105469
The relative error is 0.000000837422013
` 
We can see that the float type variable introduces more error than the double type variable. This is because the float type variable cannot represent all the digits of the terms in the Leibniz formula accurately, and thus loses some precision in each iteration. The book explains how to analyze and estimate these errors using concepts such as machine epsilon and relative error.
 
## Interpolation
 
Interpolation is a technique for finding an unknown value of a function at a given point, using some known values of the function at other points. It is useful for estimating missing data, smoothing noisy data, or approximating complex functions.
 
The book covers various methods of interpolation, such as polynomial interpolation, Lagrange interpolation, Newton interpolation, divided differences, spline interpolation, and piecewise polynomial interpolation. It also discusses some properties and applications of interpolation methods, such as error bounds, convergence, stability, and curve fitting.
 
For example, consider the following table that gives some values of a function f(x) at different points x:

| x | 0 | 1 | 2 | 3 |
| --- | --- | --- | --- | --- |

| f(x) | 1 | 3 | 7 | 13 |

We can use polynomial interpolation to find a polynomial p(x) that passes through all these points. One way to do this is to use Lagrange interpolation formula:
  $$p(x) = \sum\_i=0^n f(x\_i) \prod\_j=0,j\neq i^n \fracx-x\_jx\_i-x\_j$$  
where n is the
 8cf37b1e13
 
