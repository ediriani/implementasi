while True:
    try:
        suhu = float(input("Masukkan suhu tubuh (°C): "))  
        if suhu >= 38:
            print(f"Anda demam (Suhu: {suhu}°C)")
        else:
            print(f"Anda tidak demam (Suhu: {suhu}°C)")
        break  
    except ValueError:
        print("Input tidak valid. Masukkan angka yang benar.")