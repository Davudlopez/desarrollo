import matplotlib.pyplot as plt
import numpy as np 
import time

if __name__=="__main__":
    x= np.linspace(0,10,100)
    y = np.sin(x)
    plt.ion()
    figure, ax =plt.subplots()
    linea1, =ax.plot(x,y, 'bo')
    ax.plot(x,y, 'k')
    for i in range(len(x)):
        
        new_y =np.zeros(len(x))
        new_y[i] = y[i]
        linea1.set_xdata(x)
        linea1.set_ydata(new_y)
        figure.canvas.draw()
        figure.canvas.flush_events()
        time.sleep(0.1)
   
    plt.show()
