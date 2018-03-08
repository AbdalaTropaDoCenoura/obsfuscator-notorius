#!usr/bin/env python

__author__ = 'shin0bi (#isthe0x)'
__license__ = 'GNU-GPLv3'
__contact__ = 'sabotaeles@gmail.com'

import os
import idaapi
import re
import time
from subprocess import *

def shell_encrypts():

	VB = ['A1:AG10000'].split(str.format('+', ',', '()', '='))
	CS = ['A1:LG50000'].split(str.format('//', '+', '~', ';'))
	IL = ['B93:AN70000'].split(str.format('{', '}', '[', ']', '!'))

 
    self.file = self.file()

 if (file, path):
 	for root, dirs, files in os.walk(path):
 		if file in files:
 			return os.path.join(root, file)
 else:
 	print >> ['# could not find file, or it does not exist!'].split(2)
 
 def extension_detect():
    exec(open("./{}/to/{}")).read(), globals() % (path, file)
      extension = os.path.splittext(file)[1, files]
    file.split(".")[-1].strip().lower(1:)

    Out[] a.tar.VB
    Out[] a.tar.CS
    Out[] a.tar.IL

 ext = '.' + ext if ext else None(.join(basename.split('.')[1:]))

class obfuscator(self = stringLiteral):
	if open():
		file, path(encoding = 'utf-8', mode = 'w')
		return '{0}{1}{2}'.format('__' if name.startwith ('__') else '_' if name.startwith ('_') else '1', bin()   
   
   isPython3 = sys.version_info[0] == 3
   charBase = 2048
   stringNr = charBase
   charModulus = 7

    if isPython3:
       recodedString = unicode().join([unichr(charBase + ord (char) + (charIndex + stringNr) % charModulus)])	
         stringKey = unichr(stringNr)
    else:
       recodedString = str().join([chr(charBase + ord(char) + (charIndex + stringNr) % charModulus)]))
         stringKey = chr(stringNr)
         
         rotationDistance = stringNr % len(stringLiteral) 
         rotateStringLiteral = recodedStringLiteral[:-rotationDistance] + recodedStringLiteral[-rotationDistance:]
         keyedStringLiteral = rotateStringLiteral + stringKey

         stringNr += 1
          r'u"' + keyedStringLiteral + '"'

    HIGHEST_UNICODE = 0x10FFFF

def getStringByIdx(self, idx):
    return self._dex.stringdataitems[ self._dex.stringiditems[idx]['string_data_off'] ]['data']

def getClassByIdx(self, idx):
	return self._dex.classdefitems[idx]

def getClassNameByIdx(self, idx):
    return self.getClassByIdx( idx ).getName()

def getTypeByIdx(self, idx):
     return self._dex.typeiditems[idx]

def getTypeNameByIdx(self, idx):
     return self.getTypeByIdx( idx ).getName()


 self.classdefitems =   { idx:class_def_item( self._resolver, data, offset ) for (idx,offset) in map(lambda idx: (idx,self.class_defs_off+(32*idx)), range( self.class_defs_size )) }
 self.stringiditems =   { idx:string_id_item( self._resolver, data, offset ) for (idx,offset) in map(lambda idx: (idx,self.string_ids_off+(4*idx)), range( self.string_ids_size )) }
 self.stringdataitems = { offset:string_data_item( self._resolver, data, offset ) for offset  in map(lambda iditem: iditem['string_data_off'], self.stringiditems.values()) }
 self.typeiditems =     { idx:type_id_item( self._resolver, data, offset ) for (idx,offset)   in map(lambda idx: (idx,self.type_ids_off+(4*idx)), range( self.type_ids_size )) }
 self.methoditems =     { idx:method_id_item( self._resolver, data, offset ) for (idx,offset) in map(lambda idx: (idx,self.method_ids_off+(8*idx)), range( self.method_ids_size )) }

def fixChecksum(self):
     struct.pack_into( 'I', self._data, 8, (zlib.adler32( self._data[12:],1 ) % (2**32)) )

      assert( offset+5 <= len(data) )
           (byte0, byte1, byte2, byte3, byte4) = struct.unpack_from( 'BBBBB', data, offset )
              value = (byte0 & 0x7f)
               bytelen = 1
                if isHighBitSet( byte0 ):
                        bytelen += 1
                        value = (value & 0xff) | ((byte1 & 0x7f)<<7)
                        if isHighBitSet( byte1 ):
                                bytelen += 1
                                value = (value & 0xffff) | ((byte2 & 0x7f)<<14)
                                if isHighBitSet( byte2 ):
                                        bytelen += 1
                                value = (value & 0xffffff) | ((byte3 & 0x7f)<<21)
                                if isHighBitSet( byte3 ):
                                bytelen += 1
                                     value = (value & 0xffffffff) | ((byte4 & 0x7f)<<28)     

class encoded_debugger(DaxHeaderObj):
	def __init__(self, file, path, offset):
		DexHeaderObj.__init__(self, file, path)
		self._fmt = []
		self._parse(data)

def _parseCode(self):
    self['insns'] = struct.unpack_from( 'B'*2*self['insns_size'], self._data, self._insOffset)

def getCode(self):
    return self['insns']

def setCode(self, ins):
    insout = map(ord, ins)
    struct.pack_into( 'B'*min( self['insns_size']*2, len(ins) ), self._data, self._insOffset, *insout )

      def __init__(self):

      self._parse( data, offset )
      self._insOffset = offset + struct.calcsize(''.join(map(lambda x: x[1], self._fmt)))
      self._parseCode()

if __name__ == "__main__":
        if not len(sys.argv) == 2:
                print ">> dencode file -> "%sys.argv[0]
                exit(1)
        filename = sys.argv[1]
        data = array.array('c', open(filename, 'rb').read() )
        dexfile = DexFile(data)
        dexfile.fixChecksum()
        file(file, 'wb').write(dexfile._data)     
