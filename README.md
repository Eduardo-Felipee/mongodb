Fred> db.Fred.insertMany([{Descricao: "Computador Dell OptiPlex 3080", Marca: "Dell", Modelo: "OptiPlex 3080", Fabricacao: "2023", Configuracao: {Processador: "Intel Core i5", Memoria: "16GB", Disco: "512 SSD", Monitor: "24 inch", Teclado: "Padrão", Mouse: "Óptico", Impressora: "HP LaserJet" }, Programas: ["Windows 10", "Microsoft Office", "Adobe Reader"],
...  Aquisicao: "01/10/2024", Valor: 4500.00}]);
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670240ef1b04fdc83f9e72') }
}
Fred> db.Fred.find()
[
  {
    _id: ObjectId('66670240ef1b04fdc83f9e72'),
    Descricao: 'Computador Dell OptiPlex 3080',
    Marca: 'Dell',
    Modelo: 'OptiPlex 3080',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'Intel Core i5',
      Memoria: '16GB',
      Disco: '512 SSD',
      Monitor: '24 inch',
      Teclado: 'Padrão',
      Mouse: 'Óptico',
      Impressora: 'HP LaserJet'
    },
    Programas: [ 'Windows 10', 'Microsoft Office', 'Adobe Reader' ],
    Aquisicao: '01/10/2024',
    Valor: 4500
  }
]
Fred> db.Fred.insertMany([{Descricao:"Computador HP Pavilion 27", Marca: "HP", Modelo: "Pavilion 27", Fabricacao: "2023", Configuracao: { Processador: "AMD Ryzen 7", Memoria: "32GB", Disco: "1TB SSD", Monitor: "27 inch", Teclado: "Mecânico", Mouse: "Óptico", Impressora: "Canon Pixma" }, Programas:["Windows 11", "Microsoft Office", "Photoshop"], Aquisicao: "15/02/2024", Valor: 6000.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670479ef1b04fdc83f9e73') }
}
Fred> db.Fred.insertMany([{Descricao: "Computador Lenovo ThinkPad T14s", Marca: "Lenovo",  Modelo: "ThinkPad T14s", Fabricacao: "2023", Configuracao: {  Processador: "AMD Ryzen 5", Memoria: "8GB",  Disco: "256GB SSD", Monitor: "14 inch", Teclado: "Retroiluminado",  Mouse: "TrackPoint" }, Programas: ["Windows 11", "Microsoft Office", "Zoom"], Aquisicao:"25/09/2022", Valor: 3500.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('6667063def1b04fdc83f9e74') }
}
Fred> db.Fred.insertMany([{Descricao: "Computador Asus ROG Strix G15", Marca: "Asus", Modelo: "ROG Strix G15",  Fabricacao: "2021", Configuracao: { Processaodor: "Intel Core i7", Memoria: "16GB",  Disco: "512GB SSD", Monitor: "15.6 inch", Teclado: "RGB",  Mouse: "Gaming"}, Programas: ["Windows 11", "Steam", "Discord"],  Aquisicao: "11/05/2020", Valor: 4500.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('666707c8ef1b04fdc83f9e75') }
}
Fred> db.Fred.insertMany([{Descricao: "Computador Apple Mac mini", Marca: "Apple",  Modelo: "Mac mini", Fabricacao: "2023", Configuracao: { Processador: "Apple M1", Memoria: "8GB",  Disco: "256GB SSD", Monitor: "Sem monitor", Teclado: "Sem teclado",  Mouse: "Mouse com fio" },  Programas: ["macOS", "Safari", "iTunes"],  Aquisicao: "2023-07-20",   Valor: 2000.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670911ef1b04fdc83f9e76') }
}
Fred> db.Fred.find()
[
  {
    _id: ObjectId('66670240ef1b04fdc83f9e72'),
    Descricao: 'Computador Dell OptiPlex 3080',
    Marca: 'Dell',
    Modelo: 'OptiPlex 3080',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'Intel Core i5',
      Memoria: '16GB',
      Disco: '512 SSD',
      Monitor: '24 inch',
      Teclado: 'Padrão',
      Mouse: 'Óptico',
      Impressora: 'HP LaserJet'
    },
    Programas: [ 'Windows 10', 'Microsoft Office', 'Adobe Reader' ],
    Aquisicao: '01/10/2024',
    Valor: 4500
  },
  {
    _id: ObjectId('66670479ef1b04fdc83f9e73'),
    Descricao: 'Computador HP Pavilion 27',
    Marca: 'HP',
    Modelo: 'Pavilion 27',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'AMD Ryzen 7',
      Memoria: '32GB',
      Disco: '1TB SSD',
      Monitor: '27 inch',
      Teclado: 'Mecânico',
      Mouse: 'Óptico',
      Impressora: 'Canon Pixma'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'Photoshop' ],
    Aquisicao: '15/02/2024',
    Valor: 6000
  },
  {
    _id: ObjectId('6667063def1b04fdc83f9e74'),
    Descricao: 'Computador Lenovo ThinkPad T14s',
    Marca: 'Lenovo',
    Modelo: 'ThinkPad T14s',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'AMD Ryzen 5',
      Memoria: '8GB',
      Disco: '256GB SSD',
      Monitor: '14 inch',
      Teclado: 'Retroiluminado',
      Mouse: 'TrackPoint'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'Zoom' ],
    Aquisicao: '25/09/2022',
    Valor: 3500
  },
  {
    _id: ObjectId('666707c8ef1b04fdc83f9e75'),
    Descricao: 'Computador Asus ROG Strix G15',
    Marca: 'Asus',
    Modelo: 'ROG Strix G15',
    Fabricacao: '2021',
    Configuracao: {
      Processaodor: 'Intel Core i7',
      Memoria: '16GB',
      Disco: '512GB SSD',
      Monitor: '15.6 inch',
      Teclado: 'RGB',
      Mouse: 'Gaming'
    },
    Programas: [ 'Windows 11', 'Steam', 'Discord' ],
    Aquisicao: '11/05/2020',
    Valor: 4500
  },
  {
    _id: ObjectId('66670911ef1b04fdc83f9e76'),
    Descricao: 'Computador Apple Mac mini',
    Marca: 'Apple',
    Modelo: 'Mac mini',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'Apple M1',
      Memoria: '8GB',
      Disco: '256GB SSD',
      Monitor: 'Sem monitor',
      Teclado: 'Sem teclado',
      Mouse: 'Mouse com fio'
    },
    Programas: [ 'macOS', 'Safari', 'iTunes' ],
    Aquisicao: '2023-07-20',
    Valor: 2000
  }
]
Fred> db.Fred.insertMany([{Descricao: "Computador Dell Inspiron 15", Marca: "Dell",  Modelo: "Inspiron 15", Fabricacao: "2022",  Configuracao: { Processador: "Intel Core i3", Memoria: "8GB",  Disco: "256GB SSD", Monitor: "15.6 inch",  Teclado: "Padrão", Mouse: "Touchpad" }, Programas: ["Windows 10", "Microsoft Office", "Google Chrome"], Aquisicao: "15/05/2020", Valor: 2500.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670aafef1b04fdc83f9e77') }
}
Fred> db.Fred.insertMany([{Descricao: "Computador Acer Predator Helios 300",   Marca: "Acer", Modelo: "Predator Helios 300",  Fabricacao: "2023", Configuracao: { Processador: "Intel Core i7",   Memoria: "32GB", Disco: "1TB SSD", Monitor: "15.6 inch", Teclado: "RGB", Mouse: "Gaming" },  Programas: ["Windows 11", "Steam", "Discord"], Aquisicao: "20/10/2021", Valor: 5000.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670bc3ef1b04fdc83f9e78') }
}
Fred> db.Fred.insertMany([{Descricao:  "Computador HP Envy 13",  Marca: "HP", Modelo: "Envy 13",  Fabricacao: "2023", Configuracao: { Processador: "Intel Core i5", Memória: "16GB", Disco: "512GB SSD", Monitor: "13.3 inch", Teclado: "Retroiluminado",  Mouse: "Touchpad" }, Programas: ["Windows 11", "Microsoft Office", "Zoom"], Aquisicao: "08/11/2022", Valor: 3800.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670d62ef1b04fdc83f9e79') }
}
Fred> db.Fred.insertMany([{Descricao: "Computador Lenovo Yoga C940", Marca: "Lenovo", Modelo: "Yoga C940",  Fabricacao: "2022", Configuracao: { Processador: "Intel Core i7", Memoria: "16GB",  Disco: "512GB SSD", Monitor: "14 inch", Teclado: "Teclado retroiluminado",   Mouse: "Touchpad" }, Programas: ["Windows 10", "Microsoft Office", "Adobe Photoshop"], Aquisicao: "05/10/2023",  Valor: 3500.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670f27ef1b04fdc83f9e7a') }
}
Fred> db.Fred.find()
[
  {
    _id: ObjectId('66670240ef1b04fdc83f9e72'),
    Descricao: 'Computador Dell OptiPlex 3080',
    Marca: 'Dell',
    Modelo: 'OptiPlex 3080',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'Intel Core i5',
      Memoria: '16GB',
      Disco: '512 SSD',
      Monitor: '24 inch',
      Teclado: 'Padrão',
      Mouse: 'Óptico',
      Impressora: 'HP LaserJet'
    },
    Programas: [ 'Windows 10', 'Microsoft Office', 'Adobe Reader' ],
    Aquisicao: '01/10/2024',
    Valor: 4500
  },
  {
    _id: ObjectId('66670479ef1b04fdc83f9e73'),
    Descricao: 'Computador HP Pavilion 27',
    Marca: 'HP',
    Modelo: 'Pavilion 27',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'AMD Ryzen 7',
      Memoria: '32GB',
      Disco: '1TB SSD',
      Monitor: '27 inch',
      Teclado: 'Mecânico',
      Mouse: 'Óptico',
      Impressora: 'Canon Pixma'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'Photoshop' ],
    Aquisicao: '15/02/2024',
    Valor: 6000
  },
  {
    _id: ObjectId('6667063def1b04fdc83f9e74'),
    Descricao: 'Computador Lenovo ThinkPad T14s',
    Marca: 'Lenovo',
    Modelo: 'ThinkPad T14s',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'AMD Ryzen 5',
      Memoria: '8GB',
      Disco: '256GB SSD',
      Monitor: '14 inch',
      Teclado: 'Retroiluminado',
      Mouse: 'TrackPoint'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'Zoom' ],
    Aquisicao: '25/09/2022',
    Valor: 3500
  },
  {
    _id: ObjectId('666707c8ef1b04fdc83f9e75'),
    Descricao: 'Computador Asus ROG Strix G15',
    Marca: 'Asus',
    Modelo: 'ROG Strix G15',
    Fabricacao: '2021',
    Configuracao: {
      Processaodor: 'Intel Core i7',
      Memoria: '16GB',
      Disco: '512GB SSD',
      Monitor: '15.6 inch',
      Teclado: 'RGB',
      Mouse: 'Gaming'
    },
    Programas: [ 'Windows 11', 'Steam', 'Discord' ],
    Aquisicao: '11/05/2020',
    Valor: 4500
  },
  {
    _id: ObjectId('66670911ef1b04fdc83f9e76'),
    Descricao: 'Computador Apple Mac mini',
    Marca: 'Apple',
    Modelo: 'Mac mini',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'Apple M1',
      Memoria: '8GB',
      Disco: '256GB SSD',
      Monitor: 'Sem monitor',
      Teclado: 'Sem teclado',
      Mouse: 'Mouse com fio'
    },
    Programas: [ 'macOS', 'Safari', 'iTunes' ],
    Aquisicao: '2023-07-20',
    Valor: 2000
  },
  {
    _id: ObjectId('66670aafef1b04fdc83f9e77'),
    Descricao: 'Computador Dell Inspiron 15',
    Marca: 'Dell',
    Modelo: 'Inspiron 15',
    Fabricacao: '2022',
    Configuracao: {
      Processador: 'Intel Core i3',
      Memoria: '8GB',
      Disco: '256GB SSD',
      Monitor: '15.6 inch',
      Teclado: 'Padrão',
      Mouse: 'Touchpad'
    },
    Programas: [ 'Windows 10', 'Microsoft Office', 'Google Chrome' ],
    Aquisicao: '15/05/2020',
    Valor: 2500
  },
  {
    _id: ObjectId('66670bc3ef1b04fdc83f9e78'),
    Descricao: 'Computador Acer Predator Helios 300',
    Marca: 'Acer',
    Modelo: 'Predator Helios 300',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'Intel Core i7',
      Memoria: '32GB',
      Disco: '1TB SSD',
      Monitor: '15.6 inch',
      Teclado: 'RGB',
      Mouse: 'Gaming'
    },
    Programas: [ 'Windows 11', 'Steam', 'Discord' ],
    Aquisicao: '20/10/2021',
    Valor: 5000
  },
  {
    _id: ObjectId('66670d62ef1b04fdc83f9e79'),
    Descricao: 'Computador HP Envy 13',
    Marca: 'HP',
    Modelo: 'Envy 13',
    Fabricacao: '2023',
    Configuracao: {
      Processador: 'Intel Core i5',
      'Memória': '16GB',
      Disco: '512GB SSD',
      Monitor: '13.3 inch',
      Teclado: 'Retroiluminado',
      Mouse: 'Touchpad'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'Zoom' ],
    Aquisicao: '08/11/2022',
    Valor: 3800
  },
  {
    _id: ObjectId('66670f27ef1b04fdc83f9e7a'),
    Descricao: 'Computador Lenovo Yoga C940',
    Marca: 'Lenovo',
    Modelo: 'Yoga C940',
    Fabricacao: '2022',
    Configuracao: {
      Processador: 'Intel Core i7',
      Memoria: '16GB',
      Disco: '512GB SSD',
      Monitor: '14 inch',
      Teclado: 'Teclado retroiluminado',
      Mouse: 'Touchpad'
    },
    Programas: [ 'Windows 10', 'Microsoft Office', 'Adobe Photoshop' ],
    Aquisicao: '05/10/2023',
    Valor: 3500
  }
]
Fred> db.Fred.insertMany([{Descricao: "Computador Lenovo Yoga C940", Marca: "Lenovo", Modelo: "Yoga C940", Fabricacao: "2022",  Configuracao: { Processador: "Intel Core i7", Memoria: "16GB",  Disco: "512GB SSD", Monitor: "14 inch", Teclado: "Teclado retroiluminado", Mouse: "Touchpad" },  Programas: ["Windows 10", "Microsoft Office", "Adobe Photoshop"], Aquisicao: "11/03/2022",   Valor: 3500.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('6667108aef1b04fdc83f9e7b') }
}
