// 00-Bienvenido

    #include<stdio.h>;
    #include<stdlib.h>;
    int nbro=2,edad=21;
    float hei=1.83,wei=78.5;
    char nom[7]="Cristo";

    main()
    {
        printf("\n \t Bienvenido \n \t");
        system("pause");
        printf("\n \t %s , tienes %d años, pesas %f kilos y mides %f metros. \n Además, tienes %d hermanos",nom,edad,wei,hei,nbro);
    }


// 01-Saludo

    #include<stdio.h>
    #include<stdlib.h>
    main()
    {
      printf("\n\t Esta es la clase de");
      printf("\n\t Fundamentos de Programaci%cn \n\n\n\t",162);
      system("pause");
    }

// 02-Carátula

    #include<stdio.h>
    #include<stdlib.h>

    void  caratula(void)
    {
        system ("color 5F");
        printf("\n\t Instituto Polit%ccnico Nacional",130);
        printf("\n\t ESIME TICOM%cN: \n \t Ingenier%ca Aeron%cutica  \n \t Fundamentos de Programaci%cn",160,161,160,162);
        printf("\n\t Cristopher R%cmulo S%cnchez \n\n\n\t",162,160);
    }

    main()
    {
        caratula();
        system("pause");
    }


![image](https://user-images.githubusercontent.com/111446231/217905115-848d9a3d-6206-42eb-9ca8-c8a292c634eb.png)

// 03-Personaje

    #include<stdio.h>
    #include<stdlib.h>

    void  personaje(void)
    {
        printf("\n\t Nombre: \t\t\t Augusta Ada King o Ada Byron ");
        printf("\n\t Fecha de nacimiento: \t\t 10 de diciembre de 1815, Londres, Reino Unido ");
        printf("\n\t Hechos Relevantes: \t\t Es considerada la primer programadora al crear un algoritmo in%cdito en ese entonces pensado para ser procesado por una m%cquina",130,160);
        printf("\n\t Fecha de Fallecimiento: \t 27 de noviembre de 1852, Marylebone, Londres, Reino Unido");
        printf("\n\t ¿Porque te agrada?: \t\t Honestamente, siempre me ha parecido atractiva la est%ctica steampunk y al conocer su historia y aportes Ada Byron me da esa sensaci%cn de innovaci%cn en un mundo del pasado y de una forma m%cs realista",130,162,162,160);

    }

    main()
    {
        personaje();
        system("pause");
    }


//04-Mis_Datos

    #include<stdio.h>;
    #include<stdlib.h>;
    int nbro=2,edad=21;
    float hei=1.83,wei=78.5;
    char nom[7]="Cristo";

    void misdatos(void)
    {
        system("color 5F");
        printf("\n \t Bienvenido, \n \t %s  tienes %d a%cos, pesas %.2f kilos y mides %.2f metros. \n\t Adem%cs, tienes %d hermanos \n\t",nom,edad,164,wei,hei,160,nbro);
    }

    main()
    {
        misdatos();
        system("pause");
    }
