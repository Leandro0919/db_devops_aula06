from unittest import TestCase
	#Operacoes().soma([1, 3])	

calss TestOperacoes(TestCase):
	def setUp(self):
		self.operacoes = Op

	def test soma(self):
		self.assertEqual(self.operacoes.soma([1 , 3]), 4, 'Deveria ser 4')
	