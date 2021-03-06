# Proposal
Proposal as Part 3 of the Challenge Questions

There are two figures:
1.  Figure 1:  Dowry_Deaths_Access_To_Toilets.png
2.  Figure 2:  TV_Good_Kitchen_Indoor_Toilets.png

Figure 1:
    The figure shows the relation between crimes against women as arrests-per-million-residents and the
    accessibility of toilets.  The data is aggregated statewise.
    
    This figure was made using data from two sources:
    1.  https://data.gov.in/resources/persons-arrested-under-crime-against-women-during-2001-2012/
        The title is: "Persons arrested under crime against Women during 2001-2012"
        The crime heads are:  
        (a) 'RAPE', 
        (b)  'KIDNAPPING AND ABDUCTION', 
        (c)  'DOWRY DEATHS',
        (d)  'ASSAULT ON WOMEN WITH INTENT TO OUTRAGE HER MODESTY',
        (e)  'INSULT TO THE MODESTY OF WOMEN',
        (f)  'CRUELTY BY HUSBAND OR HIS RELATIVES (IPC SECTION 498A)',
        (g) 'IMPORTATION OF GIRLS FROM FOREIGN COUNTRY',
        (h)  'IMMORAL TRAFFIC (P) ACT', 'DOWRY PROHIBITION ACT',
        (i)  'INDECENT REPRESENTATION OF WOMEN (P) ACT',
        (j) 'COMMISSION OF SATI (P) ACT', 'TOTAL CRIMES AGAINST WOMEN'
        The data was taken from http://www.ncrb.gov.in/ (National Crimes Record Bureau)
    2.   https://data.gov.in/resources/percentage-awc-having-toilet-facilities/
        The title is: "Percentage of AWC having toilet Facilities"
        The data was taken from http://planningcommission.gov.in/ (Planning Commission)
        The data was also aggregated by state.  
    The data is complied in rape_vs_toilet.csv

Figure 2:
    Since Figure 1 seems to show a relation between toilet access and respect for women statewise, 
    it was interesting to explore the correlations in the sub-districts of one large state.
    The state chosen was Maharashtra since the districts here show wide variety in affluence.
      
    The figure 2 shows the relation between the number of households having a good kitchen and 
    the number with indoor toilets in both urban and rural areas of Maharashtra.
    A good kitchen is one that is (a) Indoors and (b) uses LPG as fuel.
    
    Two more graphs show the relation between a good kitchen and TV ownership.
    It is seen that urban areas show a strong correlation between good kitchens and indoor toilets.
    Rural areas also show a strong correlation but weaker than urban areas.  
    Both regions show a very strong relationship between good kitchens and TV ownership.
    
    The data is taken from the 2011 Indian Census' Households Data: http://www.censusindia.gov.in/2011census/Hlo-series/hlo.html  
    The data is reported as number of households in various tehsils (sub-districts) that have indoor toilets, TVs, LPG kitchens etc.
    
    The data is complied in three files:
    mah_assets_tv.csv  : for asset (including TV) ownership
    mah_kitchen.csv    : for kitchen details
    mah_latrine.csv    : for toilet details
      




