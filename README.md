# <u><b>Warts Immunotherapy</u></b>
<b> Immunotherapy uses the patient's own immune system to fight the warts. This treatment is used when the warts remain despite other treatments. One type of immunotherapy involves applying a chemical, such as diphencyprone (DCP), to the warts. A mild allergic reaction occurs around the treated warts. <u>This is an industry ready project that allows you to enter your details and confirm if your warts the patient has been infected with is treatable using immunotherapy. </b></u>

***
## <u><b>Softwares and Tools</u></b>

- [GitHub](https://www.github.com/ibvhim)
- [HerokuApp](https://www.heroku.com)
- [VS Code IDE](https://code.visualstudio.com/)
- [GitCLI](https://git-scm.com/docs/gitcli)
- [Heroku](https://heroku.com)

***
## <u><b>Steps</u></b>

1. Once the data has been processed and the best model had been selected <b>[Random Forest Classifier - 94%]</b>

2. A GitHub repository was created with the Jupyter notebook and the saved model.

3. The repository was cloned by entering the following command in the command prompt.
    <i><pre><code> git clone https://github.com/ibvhim/Warts_Immunotherapy.git </pre></code></i>

4. Data was imported into VSCode and a new enviroment was created.
    <i><pre><code> conda create -p venv python==3.7 -y </pre></code></i>

5. A `requirements.txt` file was created, which contained all of the required libraries used in the jupyter notebook.
    <i><pre><code> pip install -r requirements.txt </pre></code></i>
    
6. Once the Flask API [`app.py`], HTML [`index.html`] page, `Dockerfile` and the `main.yaml` files were created, the page was deployed in the local server to test the application.
    <i><pre><code> python app.py </pre></code></i>
   
7.  The files were commited to the GitHub repository and then deployed in Heroku
    <i><pre><code> git add . </pre></code></i>
    <i><pre><code> git commit -m "changes commited" </pre></code></i>
    <i><pre><code> git push origin main </pre></code></i>
    
8. The docker container was therefore succesfully deployed in Heroku!

***
## <u><b>Snapshots</u></b>
![image](https://user-images.githubusercontent.com/109512718/199005674-f6194ecc-be52-4e13-8299-f770e15393c9.png)

***


    


