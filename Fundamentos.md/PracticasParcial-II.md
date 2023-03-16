# Prácticas II Parcial
//22-Positivo Negativo

    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    void imprime(int);

    main()
    {
      system("color 1F");
      printf("\n\n\t Positivo Y negativo");
      datos();
      system("pause");
    }

    void datos(void)
    {
      int n;
      printf("\n\t Ingrese un valor: \n");
      scanf("%d",&n);
      imprime(n);
    }

    void imprime(int n)
    {
      if(n>0) {printf("\n\t El numero es positivo\n\n\t");}
      if(n==0){printf("\n\t El numero es neutro\n\n\t");}
      if(n<0) {printf("\n\t El numero es negativo\n\n\t");}
    }

//23-LaRecta

    #include<stdio.h>
    #include<stdlib.h>
    #include <math.h>
    #include <conio.h>

    void datos(void);
    float Pen(float,float,float,float);
    float PM(float,float);
    void imprime(float,float,float);

    main()
    {
        printf("\n\t\t Pendiente y punto medio");
        datos();
        system("pause");
    }

    void datos(void)
    {
        float x1,x2,y1,y2,p,mx,my;
        printf("\n\t Ingresa loas coordenadas x,y de los puntos A y B, respectivamente:\n");
        scanf("%f%f%f%f",&x1,&y1,&x2,&y2);
        p= Pen(x1,x2,y1,y2);
        mx= PM(x1,x2);
        my= PM(y1,y2);
        imprime(p,mx,my);
    }

    float Pen(float x1,float y1,float x2,float y2)
    {
        float p;
        p=((y2-y1)/(x2-x1));
        return p;
    }


    float PM(float z1,float z2)
    {
        float pm;
        pm=((z2+z1)/(2));
        return pm;
    }


    void imprime(float p,float mx,float my)
    {
        printf("\n\t La pendiente de la recta AB es %.2f \n\t y las coordenadas del punto medio entre A y B es M(%.2f ; %.2f)\n\n",p,mx,my);
    }
    
24- Angúlos

    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    void imprime(int);

    main()
    {
      system("color 1F");
      printf("\n\n\t Angulo");
      datos();
      system("pause");
    }

    void datos(void)
    {
      int n;
      printf("\n\t Ingrese un angulo: \n");
      scanf("%d",&n);
      imprime(n);
    }

    void imprime(int n)
    {
      if(n>=0 & n<90) {printf("\n\t %d es angulo agudo\n\n\t",n);}
      if(n>90 & n<180){printf("\n\t %d es angulo obtuso\n\n\t",n);}
      if(n==90){printf("\n\t %d es angulo recto\n\n\t",n);}
      if(n==180){printf("\n\t %d es angulo llano\n\n\t",n);}
      if(n>180 & n<360){printf("\n\t %d es angulo concavo\n\n\t",n);}
      if(n==360){printf("\n\t %d es angulo completo\n\n\t",n);}

    }
    
    
25-EtapaDeVida

26-MayorDe3

    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    void imprime(int);

    main()
    {
      system("color 1F");
      printf("\n\n\t El amyor de los 3");
      datos();
      system("pause");
    }

    void datos(void)
    {
      int n;
      printf("\n\t Ingrese los tres numeros: \n");
      scanf("%d%d%d",&n,&n2,&n3);
      imprime(n,n2,n3);
    }

    void imprime(int n,int n2,int n3)
    {
      if(n<=n2 & n2<n3 | n2<=n & n<n3) {printf("\n\t %d es angulo agudo\n\n\t",n);}
      if(n3<=n2 & n2<n | n2<=n3 & n3<n){printf("\n\t %d es angulo recto\n\n\t",n);}
      if(n3<=n & n<n2 | n<=n3 & n3<n2){printf("\n\t %d es angulo llano\n\n\t",n);}
      if(){printf("\n\t %d es angulo concavo\n\n\t",n);}
      if(----){printf("\n\t %d es angulo completo\n\n\t",n);}

    }

27-IMC

