---
description: A Step-by-Step guide on how to run the fairness module by running all of its dependencies and their virtual environments first before lasltly running the fairness module
---

````markdown
## Workflow: Start all Responsible AI Toolkit modules and do not test each and every service.

1. **Model Details – change directory & activate venv**

   ```powershell
   cd C:\Visual_studio_code\Infosys-Responsible-AI-Toolkit\responsible-ai-model-detail
   .\.venv\Scripts\activate
````

2. **Model Details – go to `src` folder**

   ```powershell
   cd C:\Visual_studio_code\Infosys-Responsible-AI-Toolkit\responsible-ai-model-detail\workbench\src
   ```

3. **Model Details – run `main.py`**

   ```powershell
   python main.py
   ```

4. **Open a new terminal**
   Keep the Model Details terminal running.

---

5. **Reporting Tool – change directory & activate venv (in new terminal)**

   ```powershell
   cd C:\Visual_studio_code\Infosys-Responsible-AI-Toolkit\responsible-ai-reporting-tool
   .\.venv\Scripts\activate
   ```

6. **Reporting Tool – go to `src` folder**

   ```powershell
   cd C:\Visual_studio_code\Infosys-Responsible-AI-Toolkit\responsible-ai-reporting-tool\wrapper\src
   ```

7. **Reporting Tool – run `main.py`**

   ```powershell
   python main.py
   ```

8. **Open another new terminal**
   Keep the previous ones running.

---

9. **Admin Tool – change directory & activate venv (in new terminal)**

   ```powershell
   cd C:\Visual_studio_code\Infosys-Responsible-AI-Toolkit\responsible-ai-admin\responsible-ai-admin
   .\.venv\Scripts\activate
   ```

10. **Admin Tool – go to `src` folder**

    ```powershell
    cd C:\Visual_studio_code\Infosys-Responsible-AI-Toolkit\responsible-ai-admin\responsible-ai-admin\src
    ```

11. **Admin Tool – run `main.py`**

    ```powershell
    python main.py
    ```

12. **Open another new terminal**
    Keep the previous ones running.

---

13. **Fairness module – change directory & activate venv (in new terminal)**

    ```powershell
    cd C:\Visual_studio_code\Infosys-Responsible-AI-Toolkit\responsible-ai-fairness
    .\.venv\Scripts\activate
    ```

14. **Fairness module – go to `src` folder**

    ```powershell
    cd C:\Visual_studio_code\Infosys-Responsible-AI-Toolkit\responsible-ai-fairness\responsible-ai-fairness\src
    ```

15. **Fairness module – run `main_api.py`**

    ```powershell
    python main_api.py
    ```

```
::contentReference[oaicite:0]{index=0}
```