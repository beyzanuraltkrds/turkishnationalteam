def kadro_siniflandirma(satır):
    satır = satır.strip()
    liste = satır.split(",")

    if len(liste) < 4:
        return None, None

    futbolcu = liste[0]
    mevkii = liste[1].strip()
    takımı = liste[2]
    yaşı = int(liste[3])

    if mevkii == "Kaleci":
        mevkii = "Kaleci"
    elif mevkii == "Stoper":
        mevkii = "Stoper"
    elif mevkii == "Sol Bek":
        mevkii = "Sol Bek"
    elif mevkii == "Sağ Bek":
        mevkii = "Sağ Bek"
    elif mevkii == "Ön Libero":
        mevkii = "Ön Libero"
    elif mevkii == "Merkez Orta Saha":
        mevkii = "Merkez Orta Saha"
    elif mevkii == "On Numara":
        mevkii = "On Numara"
    elif mevkii == "Sol Kanat":
        mevkii = "Sol Kanat"
    elif mevkii == "Sağ Kanat":
        mevkii = "Sağ Kanat"
    else:
        mevkii = "Santrafor"

    return futbolcu + "-------------> " + mevkii + "\n"

with open("kadro.txt", "r", encoding="utf-8") as file:
    eklenecek_kaleci = []
    eklenecek_stoper = []
    eklenecek_solbek = []
    eklenecek_sagbek = []
    eklenecek_onlibero = []
    eklenecek_merkezortasaha = []
    eklenecek_onnumara = []
    eklenecek_solkanat = []
    eklenecek_sagkanat = []
    eklenecek_santrafor = []

    for i in file:
        mevkii = kadro_siniflandirma(i)
        if "Kaleci" in mevkii:
            eklenecek_kaleci.append(mevkii)
        elif "Stoper" in mevkii:
            eklenecek_stoper.append(mevkii)
        elif "Sol Bek" in mevkii:
            eklenecek_solbek.append(mevkii)
        elif "Sağ Bek" in mevkii:
            eklenecek_sagbek.append(mevkii)
        elif "Ön Libero" in mevkii:
            eklenecek_onlibero.append(mevkii)
        elif "Merkez Orta Saha" in mevkii:
            eklenecek_merkezortasaha.append(mevkii)
        elif "On Numara" in mevkii:
            eklenecek_onnumara.append(mevkii)
        elif "Sol Kanat" in mevkii:
            eklenecek_solkanat.append(mevkii)
        elif "Sağ Kanat" in mevkii:
            eklenecek_sagkanat.append(mevkii)
        else:
            eklenecek_santrafor.append(mevkii)


    with open("kaleci.txt", "w", encoding="utf-8") as file_kaleci:
        for i in eklenecek_kaleci:
            file_kaleci.write(i)
    with open("stoper.txt", "w", encoding="utf-8") as file_stoper:
        for i in eklenecek_stoper:
            file_stoper.write(i)

    with open("solbek.txt", "w", encoding="utf-8") as file_solbek:
        for i in eklenecek_solbek:
            file_solbek.write(i)

    with open("sagbek.txt", "w", encoding="utf-8") as file_sagbek:
        for i in eklenecek_sagbek:
            file_sagbek.write(i)

    with open("onlibero.txt", "w", encoding="utf-8") as file_onlibero:
        for i in eklenecek_onlibero:
            file_onlibero.write(i)

    with open("merkezortasaha.txt", "w", encoding="utf-8") as file_merkezortasaha:
        for i in eklenecek_merkezortasaha:
            file_merkezortasaha.write(i)

    with open("onnumara.txt", "w", encoding="utf-8") as file_onnumara:
        for i in eklenecek_onnumara:
            file_onnumara.write(i)

    with open("solkanat.txt", "w", encoding="utf-8") as file_solkanat:
        for i in eklenecek_solkanat:
            file_solkanat.write(i)

    with open("sagkanat.txt", "w", encoding="utf-8") as file_sagkanat:
        for i in eklenecek_sagkanat:
            file_sagkanat.write(i)
    with open("santrafor.txt","w",encoding="utf-8") as file_santrafor:
        for i in eklenecek_santrafor:
            file_santrafor.write(i)
