import sys
import pefile
import peutils
print("Code usage: python {name of file}.py {path to file} \ne.g  python imphash_calc.py C:\Home\Downloads\obviousmalware")

pe_file = sys.argv[1]
pe = pefile.PE(pe_file)
imphash = pe.get_imphash()

print("Find Impash Below")
print(imphash)
