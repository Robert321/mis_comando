# mis_comando

db.getCollection('impAfrActa').find({"data.numDim":"DI-2022-234-2107280"})
db.getCollection('impAfrActa').find({"data.numDim":"DI-2023-401-2457450"})
db.getCollection('impDim').find({"data.num":"DI-2022-234-2107280"})
db.getCollection('message').find({"data.numDeclaracion":"ARIVV-2022-234-45"})
db.getCollection('message').find({"data.sender":"ADAKRONOS"})
db.getCollection('notificacion').find({"data.nomPro":"DI-2022-234-2107280"})
db.getCollection('impDatosMercanciaDimAforo').find({"data.dim.id":"944af26b-6a58-4705-88a1-ce23e0a8322e"},{"data.codSubAra":1})
db.getCollection('impAfrActa').find({"data.numDim":"DI-2023-401-2457450"})

db.getCollection('impDim').find({
  "data.fecTra": {
    $gte: ISODate("2023-12-22T00:00:00.000Z"),
    $lt: ISODate("2023-12-23T00:00:00.000Z")
  },"data.estAct":"EN_AFORO"
});
db.getCollection('impDim').find({"data.num":"DI-2023-201-2119666"})
db.getCollection('impAfrActa').find({"data.numDim":"DI-2023-422-2460356"})
db.getCollection('impAfrActa').find({
  "log.est.nom": "EN_AFORO",
  "log.est.usu": { $ne: "BPM" }
});

1 CASO LAVENTE ABANDONO
db.getCollection('impAbaTacExp').find({"data.datGen.numDim":"DI-2023-711-2105413"})

payload.proBpm.fecFin=ISODate("2023-05-15T00:17:42.828-04:00")
