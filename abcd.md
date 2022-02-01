{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "884aab0f",
   "metadata": {},
   "source": [
    "# Commands to be followed for using the sample data"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3e91d0fb",
   "metadata": {},
   "source": [
    "### Step-1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "a380eb3f",
   "metadata": {},
   "outputs": [],
   "source": [
    "call n10s.graphconfig.init();"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7afd7d0b",
   "metadata": {},
   "source": [
    "### Step-2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "52224232",
   "metadata": {},
   "outputs": [],
   "source": [
    "CREATE CONSTRAINT n10s_unique_uri ON (r:Resource) ASSERT r.uri IS UNIQUE"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "23c6dd14",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "5fc62eb0",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "0a8ac0bf",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.8"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
