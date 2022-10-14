# My Jupyter Notebook on IBM Watson Studio

**Annisa, occupation**

*I am interested in data science because I love Data*

### My code below is about the Gauss formula

def gaussian(x, mu, sig):
    return np.exp(-np.power(x - mu, 2.) / (2 * np.power(sig, 2.)))

x_values = np.linspace(-3, 3, 120)
for mu, sig in [(-1, 1), (0, 2), (2, 3)]:
    mp.plot(x_values, gaussian(x_values, mu, sig))

