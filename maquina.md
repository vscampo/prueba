var maquina = {
    admin: {
        pass: "ficticiaMola"
    },
    consulta: {
        saldos: function(clave, usuario) {
                    var saldo = -1;
                    for (var i = 0; i < clientes.length; i++) {
                        if (clientes[i].usuario === usuario && clientes[i].password === clave) {
                            saldo = clientes[i].presupuesto;
                            break;
                        }
                    }
                    return saldo;
        },
        gastos: function(clave, usuario) {
            var gasto = false;
            for (var i = 0, i < clientes.length; i++) {
                if (clientes[i].usuario === usuario && clientes[i].password === clave) {
                    gasto = clientes[i].gastos;
                    break;
                }   

            }

            return gasto;
        }
    }

    agregarEliminar: {
        function asignar(nombre) {
            var registrado = false;
            var vacante = false;

            for (var i = 0; i < lista.length; i++) {
                if (lista[i] === undefined) {
                    vacante = i;
                }
                if (lista[i] === nombre) {
                    registrado = i;
                }
            }

            if (registrado || registrado === 0) {
                console.warn("Ya estabas registrado!");
                console.info("Eres el asistente número", registrado);
            } else {
                if (vacante || vacante === 0) {
                    lista[vacante] = nombre;
                    console.info("Eres el asistente número", vacante);
                    console.info("Felicidades! has ocupado un asiento que estaba vacio.");
                } else {
                    lista.push(nombre);
                    console.info("Eres el asistente número", lista.length - 1);
                    console.info("No quedan asientos vacios antes que el tuyo.");
                }
            }

        },

        function quitar(nombre) {
            var registrado = false;

            for (var i = 0; i < lista.length; i++) {
                //console.log("pase por aqui...");
                //console.log(lista[i]);
                if (lista[i] === nombre) {
                    registrado = i;
                }
            }

            //console.log(registrado);

            if (registrado || registrado === 0) {
                lista[registrado] = undefined;
                console.info("El asistente " + nombre + " ha sido eliminado.");
                console.info("El asiento " + registrado + " esta vacio.");
            } else {
                console.warn("El asistente " + nombre + "... no existe!");
            }
        }

    }
};

var clientes = [{
    nombre: "alfredo",
    usuario: "alf",
    password: "alf123",
    tipoUsuario: "admin",
    gastos:[],
    presupuesto: 1000
}, {
    nombre: "rodolfo",
    usuario: "rodolf",
    password: "rodolf123",
    tipoUsuario: "user",
    gastos:[],
    presupuesto: 140
}, {
    nombre: "diego",
    usuario: "dieg",
    password: "diegf123",
    tipoUsuario: "user",
    gastos:[],
    presupuesto: 110
}];



var productos = [{
    nombre: "patatas",
    codigo: "a1",
    stock: 7,
    precio: 90
}, {
    nombre: "chocolate",
    codigo: "a2",
    stock: 10,
    precio: 60
}, {
    nombre: "zumo",
    codigo: "a3",
    stock: 10,
    precio: 30
}];



