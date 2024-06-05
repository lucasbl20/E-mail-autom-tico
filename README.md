import pyautogui
import time
pyautogui.PAUSE = 1
#pyautogui.click -> clicar em algum lugar da tela 
#pyautogui.write -> escrever um texto 
#pyautogui.press -> pressionar 1 tecla do teclado l

# pyautogui.hotkeky("ctrl", "v")
pyautogui.press("win")
pyautogui.write("chrome")
pyautogui.press("enter")

link = "https://gmail.google.com/mail/u/0/?tab=rm&ogbl#inbox"
pyautogui.write(link)
pyautogui.press("enter")

time.sleep(4)

#Passo 2: Fazer login
pyautogui.click(x=23, y=159)
time.sleep(4)
pyautogui.write("lucas2017gomess@gmail.com")
time.sleep(2)
pyautogui.press("enter")
pyautogui.press("tab")
pyautogui.write("Teste")
pyautogui.press("tab")  
pyautogui.write("Venho por meio desse escrever esse e-mail para teste :)")
time.sleep(2)
pyautogui.click(x=1307, y=999)
